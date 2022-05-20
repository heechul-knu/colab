# Deep Learning
딥러닝 수업을 위한 깃허브 입니다.

# Term Project for Final Exam
- Goal: To achieve the best performance on CIFAR-10 dataset in this class.
- You have to submit your source code and final report that describes your methods. (~11:59pm, 12th June, 2022)
- Also, you have to submit your intermediate report (~11:59pm, 25th May, 2022)
- You have to upload your accuracy on the leaderboard.
- Your submitted reports will be shared with other students.
- Selected students should give a presentation about their work. (Full credit!!)
<br>

- Evalueation metric: Top-1 classification rate (%) (Validation accuracy)
- Train data: 50000
- Validation data: 10000 (Same as the original validation dataset of CIFAR-10)
- Deep learning framework: Any framework (PyTorch, Tensorflow, Keras ...)
- Deep learning architecture: See below.
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
EfficientNet<br>
You can design your architecture.<br>
<br>
You can only use the architectures as a baseline for term project, and you can modify it while maintaining the basic form of the architectures.
<br>

# Evaluation Scores for Students
- Intermediate report (pdf, 1~2 page, 20 points)
- Final report (pdf, 4 page, 30 points)
- Final source code (5 points)
- Leader board upate (5 points)
<br>
# Leaderboard
- Upload only validation accuracy. (Not train accuracy.)
- 
<br>
<br>



# Example: baseline code (pytorch-cifar)
- github clone
```
git clone https://github.com/kuangliu/pytorch-cifar.git
```

- 실행
```
cd pytorch-cifar
python3 main.py
```

- GPU 0번으로 실행하기
```
CUDA_VISIBLE_DEVICES=0 python3 main.py
```

- main.py 수정하기
```
nano main.py
```
