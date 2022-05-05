# Deep Learning
딥러닝 수업을 위한 깃허브 입니다.

# Term Project for Final Exam
- Goal: To achieve the best performance on CIFAR-10 dataset in this class.
- Submit a report that describes your method and the results. (~11:59pm, 12th Dec. 2021, extended!!)
- I am going to share your report with other students.
- (Recommendation!) Share your source code using Github with other students.
- Workshop? Presentation? --> Top-10 students will give a presentation about their work. (09:00 am, 17th Dec. 2021)
<br>

- Evalueation metric: Top-1 classification rate (%)
- Train data: 50000
- Validation data: 10000 (Same as the original validation dataset of CIFAR-10)
- Deep learning framework: Any framework (PyTorch, Tensorflow, Keras ...)
- Deep learning architecture: Any architecture
- You can use ImageNet pre-trained model.
<br>

- You can check the state-of-the-art approaches.
- https://paperswithcode.com/sota/image-classification-on-cifar-10
- https://github.com/kuangliu/pytorch-cifar
<br>

- Model constraints!<br>
The architectures are limited as follows:
<br>

AlexNet<br>
VGG<br>
ResNet<br>
SqueezeNet<br>
DenseNet<br>
Inception v3<br>
GoogLeNet<br>
ShuffleNet v2<br>
MobileNetV2<br>
MobileNetV3<br>
ResNeXt<br>
Wide ResNet<br>
MNASNet<br>
<br>
You can only use the architectures as a baseline for term project, and you can modify it while maintaining the basic form of the architectures.
<br>
<br>



# Example: baseline code (pytorch-cifar)

# home 디렉토리로 변경
cd ~

# pip 업그레이드
pip3 install --upgrade pip

# pytorch install 
pip3 install --user -r ../requirements.txt -f https://download.pytorch.org/whl/cu110/torch_stable.html 

# 실행
cd pytorch-cifar

python3 main.py

# GPU 0번으로 실행하기
CUDA_VISIBLE_DEVICES=0 python3 main.py


# main.py 수정하기
nano main.py
