# Data-analysis-produce

* 농산물 미래 가격 데이터 예측 분석
(Python, Tensorflow, Numpy, Pandas, Jupyter Notebook, Flask, MDBootstrap)
![image](https://user-images.githubusercontent.com/59761622/134157356-c900c320-d7c1-4134-9ca7-42638dd9bc4b.png)
***
기상청의 기상자료개방포털 -> 기후통계분석 -> 통계분석란 에서 제공되는 공개 데이터와 KAMIS 농산물 유통정보의 농산물 배추의 평균 가격들의 공개 데이터를 가지고 일자, 평균온도, 최저온도, 최고온도, 강수량, 농산물 가격으로 .csv 파일에 데이터 정제 후 Pandas 라이브러리로 정제된 파일을 읽어와 Numpy 라이브러리를 활용해 데이터를 분류하고 Tensorflow로 선형회귀 모델을 활용하여 주피터 노트북에서 데이터를 학습 시켰다. 이 후 주피터 노트북에서 데이터를 학습하여 예측했던 Tensorflow 모듈이 웹에서 동작하도록 하기 위해 Flask 웹 서버, 무료 bootstrap 템플릿인 MDBootstrap으로 웹의 기본 디자인으로 활용하였으며 이를 응용하여 웹 환경에서 미래 배추 가격 데이터를 예측할 수 있도록 하였다.
***
자세한 내용은 다음 링크에서 볼 수 있다.

https://blog.naver.com/ljs1027s/222067912396
