# Deep Learning
딥러닝 수업을 위한 깃허브 입니다.

# 설치
- pip 업그레이드
```
pip3 install --upgrade pip
```

- pytorch install
```
pip3 install --user -r ../requirements.txt -f https://download.pytorch.org/whl/cu110/torch_stable.html
```

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
