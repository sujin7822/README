
![img1](img\sia_logo.png)

# AIFFEL X SIA PROJECT
* 모두의연구소 산하 인공지능 교육기관 AIFFEL과 인공지능 기반 위성/항공 영상 분석 전문기업 SI Analytics가 협력하여 진행된 기업 연계 해커톤 프로젝트로서, [위성영상 객체분할을 위한 의미론적 분할 기술] 주제에 대해 SIA로 부터 제공 받은 위성 데이터를 기반으로 프로젝트를 진행하였습니다.

## 1. 프로젝트 소개
### 개요
- 주제 : **위성영상 객체분할을 위한 의미론적 분할 기술**  
- 기간 : 2021.04.25(월)  ~ 2021.06.09(목)  
- 방식 : 팀 프로젝트
- Keyword : 의미론적 분할 (Semantic segmentation), Instance segmentation
- 배경
    * 의미론적 분할(Semantic Segmentation)은 위성으로부터 관찰되는 특정픽셀을 분류하는 방법으로써 전통적으로 많은 연구가 수행됨.
    * 인공지능 분석결과를 육안으로 분석해야하는 한계를 넘기 위해 Instance Segmentation 분석 수요 증가.
    * 객체의 ID가 구분되는 Instance Segmentation은 향후 고차원적인 분석방법을 지원.

### 프로젝트 목표
- 위성 영상에서 건물과 도로를 식별하고 객체를 분할한다.
    - 건물, 도로 각각 Semantic Segmentation
- 레벨별 스텝
    - [LV1] 건물과 도로를 각각 검출하고 결과를 합쳐서 분석한다. (일반 ★☆☆☆☆)
    - [LV2] 건물의 객체검출을 위한 학습을 수행한다. (어려움 ★★☆☆☆)
    - [LV3] 건물의 크기와 개수를 계산할 수 있도록 LV2결과를 이용해 Polygon형태로 나타내고 지도에 매핑한다. (일반 ★★☆☆☆)

### 구성원 
| 이름 | 구성 | 역할 |
| :-----: | :-----: | :----------------------------: | 
| 황무성 | 팀장 | 프로젝트 총괄, pre-processing, Road Segmentation 모델링, Instance Segmentation 모델링, 결과 분석 | 
| 배재현 | 부팀장 | 일정 관리, pre-processing, Building Segmentation 모델링, 결과 분석, GIS Mapping, GCP 운용 | 
| 권다현 | 팀원 | EDA, post-processing, Loss Function 비교 분석 | 
| 양창민 | 팀원 | SpaceNet 자료조사, post-processing, Upsampling |
| 남궁재원 | 팀원&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | EDA, Road Contour 모델링 |

### 기술 스택
- Pytorch, MMSegmentation, OpenCV, PIL, QGIS, Pandas, numpy, Matplotlib, Seaborn 외

## 2. 데이터 정의 및 EDA

### 데이터 정의

### 데이터 분석(EDA)


## 3. Level1 건물과 도로를 각각 검출하고 결과를 합쳐서 분석

### Pre-processing

### Modeling

### Loss Function research

### Upsampling

### Contour...

### Post-processing

### Test data 분석

### 데이터셋 추가

## 4. Level2 건물의 객체검출을 위한 학습을 수행

### Pre-processing

### Modeling

## 5. Level3 건물의 크기와 개수를 계산할 수 있도록 LV2결과를 이용해 Polygon형태로 나타내고 지도에 매핑

### QGIS