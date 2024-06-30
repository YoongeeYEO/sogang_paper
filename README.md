# 서강대학교 정보통신대학원 졸업논문

### Subject : 선체 균열 탐지를 위한 도메인 적응 및 데이터 증강의 효율적 혼합 적용 방안
- 선체 표면 균열 탐지를 위해 도메인 적응과 데이터 증강 기법의 효율적 혼합 적용 방안에 대한 연구
- 상대적으로 수집이 쉬운 콘크리트 표면의 정상 및 균열 이미지 데이터를 Source Domain Dataset으로 활용하여, 최종적으로 Target Domain인 선체 표면의 정상 및 균열 이미지 데이터를 분류하는 딥러닝 모델의 성능을 향상시키는 방안 탐색
---
### Recommended Requirements
```
python >= 3.8.2
opencv-python = 4.5.4.58
tensorflow = 2.8.0
tensorboard = 2.7.0
keras = 2.8.0
pytorch = 1.7.1
torchvision = 0.8.2
scipy = 1.7.1
numpy = 1.21.3
pillow = 8.4.0
pandas = 1.3.5
matplotlib = 3.4.3
```

### Method
![제안기법](https://github.com/YoongeeYEO/sogang_paper/blob/main/mehtod%20architecture.png)
- Domain Adaptation과 Data Augmentation을 동시에 적용하였을 때 Baseline 모델 대비 유의미한 성능 향상을 보임.
  - Domain Adaptation(DANN)과 Data Augmentation 기법들을 각각 단독으로 적용한 경우보다 Accuracy 최대 9.6% 향상
    ![전체 Accuracy 비교](https://github.com/YoongeeYEO/sogang_paper/blob/main/2f7349d7-8257-4959-8ccb-61de4da2f02f.jpg)

### Dataset
- [Source Domain Dataset #1](https://github.com/khanhha/crack_segmentation#Dataset)
- [Source Domain Dataset #2](https://digitalcommons.usu.edu/all_datasets/48/)
- [Source Domain Dataset #3](https://www.kaggle.com/datasets/arunrk7/surface-crack-detection)
- [Source Domain Dataset #4](https://www.kaggle.com/datasets/pauldavid22/crack50020220509t090436z001)
- [Target Domain Dataset](https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=data&dataSetSn=71447)
  
### Training🚀🚀
- run ```python code/DANN/models.py```

---
### Process of preparation
```
https://www.notion.so/97d8d90d34714017b546ad61aa8d3c1e?pvs=4
```
