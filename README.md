<div align="center">
<h1>전산물리학 과제</h1>

전산물리학 과제를 위해 사용된 레포지토리 <br>
각국의 데이터를 통해 한국의 출산율을 예측한다.
<br><br>  

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"> &nbsp;&nbsp;
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"> &nbsp;&nbsp;
<img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white">
</div>


* * *

## 진행 과정
### 데이터 수집
- OECD 페이지를 통한 데이터 수집 - https://stats.oecd.org/

### 데이터 스케일링 
- StandardScaler

### DNN 모델 생성
- Input
  - 이혼율
  - 고등교육율
  - 집값
  - 인플레이션
  - 여성 고용 비율
- Ouptut
  - 출산율
- Layer
  - 64 Dense - Input
  - 32 Dense - Hidden
  - 16 Dense - Hidden
  - 1 Dense - Output

### 모델 학습
- 100 Epochs
- 0.0005 Learning Rate
- 10 Batch Size
