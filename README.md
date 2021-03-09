# BikeSeoul
서울 자전거 따릉이   
데이터 출처: 서울열린데이터광장, 공공데이터포털   
   
  
  
## 따릉이 사용을 더 증가할 수 있는 방안이 있을까?
1. Background
2. 사람들이 따릉이를 사용하는 이유
3. 다른 지역으로 이동 / 단거리 이동 / 동일한 장소에 반납 등.. 어떤 유형이 있을까?   

### 1. Background
+ 자전거 대여소 자치구별 설치 건수 현황
![Alt text](/img/1stationNum.jpg '자치구별 설치건수')
                         <2021년 1월 31일 기준>

> 자전거 대여소가 가장 많이 설치된 자치구는 강서구임.   
> 지하철역 출구 주위에 가장 많이 설치되어 있는 자치구는 동작구이자만 동작구에 지하철이 많아서 대여소가 많은지 추가적인 분석 필요함. (간단하게 확인해보자)

+ 자치구별 지하철역수와 대여수의 관계 확인하기
<img src='/img/2trainnum.jpg' width='70%' height='70%' title='자치구별 지하철수 연관성'></img><br/>
> 자하철수가 많으면 그만큼 대여소가 많은 것을 확인함.   

+ 이용건수 전체 현황
![Alt text](/img/3overallTrend.jpg '전체트랜드')
> 일별 사용건수는 7일평균과 비교해 변동이 많은 편임.   
> 2015년부터 사용자가 꾸준히 증가하는 추세를 확인 할 수 있지만 겨울시즌에는 사용 감소폭이 큰편임.     
> 월간 트랜드로 주기적인 인사이트를 확인해보도록 하자!   

*평균값을 비교할 때는 발견하지 못했지만 월 총이용건수 그래프에서 이상한점 발견.   

![Alt text](/img/4error.jpg '데이터이상')
> 음영부분에 월평균값과 월총이용건수의 트랜드가 다른것을 확인 할 있음.   
> 확인해보니 음영부분에 데이터 중복값이 발생된것을 찾을 수 있음.
> 2019년 6월부터 11월까지 데이터 중복건수 발생 하지만 값이 조금씩 다르기때문에 가작 큰 값을 선택해서 사용하기로함.   
> 수집한 날짜에 해당 월 이용건이 입력이 되기 전이라고 생각하면 가장 높은 수치를 사용하는게 맞다는 판단임.






