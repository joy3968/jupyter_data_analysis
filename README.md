# jupyter_data_analysis
주피터를 통한 데이터 분석 자료입니다.

***
### 1.traffic_accident
시도별 교통사고 통계를 이용하여 분석한 자료입니다.

***
### 2. CCTV in Seoul
서울시 구별, CCTV의 설치 대수와 인구수와의 관계를 분석한 자료입니다.

***
### 3. crime in Seoul
서울시 구별 CCTV 갯수와 범죄율, 검거율 간의 관계를 분석한 자료입니다.

***
### 4. parking_lot
서울시 자치구별 차량 등록 대수와, 주차 공간에 대한 분석 자료입니다.

##### 결론
![parking_lot](https://user-images.githubusercontent.com/69666784/93578990-ea74d980-f9d8-11ea-9a5e-4bb4ee93e98a.PNG)

추세선을 통해 분석 해 보았을 때, 강남구는 차량등록 대수에 비해 주차공간이 넓다는 것을 알 수 있다.
***
### 5. real_estate_analysis
지역별 부동산 가격추이에 대한 시각화 자료입니다. (상대적으로 어느 지역이 많이 올랐는지 시각화)
***
##### 결론
![real_estate_analysis_1](https://user-images.githubusercontent.com/69666784/93729620-4bcac180-fc00-11ea-8140-021eb4e82334.PNG)

![real_estate_analysis_2](https://user-images.githubusercontent.com/69666784/93729622-4cfbee80-fc00-11ea-98e7-72fe68a89885.PNG)

2016년부터 2020년 사이 부동산 시세 증감률을 보았을 때 분당구, 영등포구, 강남순으로 많이 올랐다는 것을 알 수 있다.

***
#### 사용 라이브러리
+ numpy : 데이터 이용(통계)
+ pandas : 데이터 이용
+ matplotlib : 시각화
+ seaborn : 시각화
+ folium : 지도를 통한 시각화
***

#### 데이터 이용
+ 시도별 사고량 통계자료 : 공공 데이터 포털  https://www.data.go.kr/
+ 서울시 구별 CCTV 자료 : 서울 열린 데이터 광장  https://data.seoul.go.kr/
+ 서울시 범죄 현황 자료 : 서울 열린 데이터 광장  https://data.seoul.go.kr/
+ 서울시 차랑 등록 자료  : 서울 열린 데이터 광장  https://data.seoul.go.kr/
+ 서울시 주차장 통계 자료 : 서울 열린 데이터 광장  https://data.seoul.go.kr/
