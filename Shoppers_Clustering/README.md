## Project Overview / 프로젝트 개요:
* The project is based on open-source data available at https://absentdata.com/wp-content/uploads/2023/03/Mall_Customers.csv
  <br>이 프로젝트는 공개적으로 이용 가능한 오픈소스 데이터를 기반으로 합니다
* The data describes shopping mall customers with spending, income, and other dimensions.
  <br>해당 데이터는 지출, 소득 및 기타 여러 차원에 걸쳐 쇼핑몰 고객에 대한 정보를 설명합니다

## Project Objective / 프로젝트 목표:

* Understanding the target customers to help marketing team plan customer targeting strategy
  <br>마케팅 팀의 고객 타겟 전략을 수립하는데 있어 도움을 주기 위해 해당 고객을 이해하는 것을 목표로 함.
  <br>Dividing mall target customers into approachable groups using K-means Clustering Algorythm
  <br>K-means 클러스터링 알고리즘을 사용하여 쇼핑몰의 타깃 고객을 접근 가능한 그룹으로 분류
* Udentifying the most important shopping groups based on available attributes (income, age, the mall shopping score)
  <br>가용한 속성(소득, 연령, 쇼핑 점수)을 기반으로 가장 중요한 쇼핑 그룹을 식별
  <br>Creating subsets of market based on demographic behavioral criteria to better understand the target for marketing activities using summary statistics on the clusters
  <br>클러스터에 대한 요약 통계를 활용하여 인구통계학적·행동적 기준에 따른 시장 하위 집합을 생성함으로써, 마케팅 활동을 위한 타깃을 더 잘 이해하기 위함

## Summary and Conclusions / 요약 및 결론

Assuming the dataset is representative of the shopping mall customers' general population, below are the findings and recommendations.
<br>본 데이터셋이 쇼핑몰 고객 전체에 대한 대표값이라 가정할 경우 주요 결과와 제안사항은 아래와 같습니다.

| General Trends | Recommendations |
|:----------|:----------|
|There are more female shopping mall customers than male ones| <ul><li>Developing strategies to grow the male customers number: special workshops, male-oriented stores, enhancing purchase effectiveness and speed, social events for male community, rest spaces</li><li>Encouraging women to spend more with emotionally engaging marketing campaigns, feeling of comfort and safety, and personalization (social-role approach, celebrating being a woman)</li></ul>|
|Annual income of female customers is lower than that of male customers|<ul><li>Male customers: <br> Creating a habbit of spending money in the shopping mall <br> Opening pop-up stores targeting males <br> Providing premium experience opportunities </li><li>Female customers (more potential price sensitivity): <br> Providing a variety of purchse options in various price segments <br> Educating the customers on installment payment options and expanding the benefits </li></ul>|
|The older the customer, the less they are willing to spend and vice versa|Older Customers: <br> The importance of comfort: ensuring there are enough places to rest <br> Reducing stress: easy-to-understand navigation and help desks, voice-navigation stations <br> Sense of community: providing programs and activities accessible for people of older age <br> Health concerns: Encouraging self-care with special discounts, promotions, and health check-up booths <br> Accessibility: rental wheelchairs and guides|

|일반적인 경향	|권장 사항|
|:----------|:----------|
|여성 고객이 남성보다 많음| <ul><li>남성 고객 증가 전략: 워크숍, 남성 전용 매장, 소셜 이벤트, 휴식 공간 </li><li> 여성 고객 소비 촉진: 감성 마케팅, 편안함·안전감, 개인화 전략 </li></ul>|
|여성 고객 소득이 남성보다 낮음|	<ul><li> 남성: 소비 습관 형성, 팝업 스토어, 프리미엄 경험 제공 </li><li> 여성: 다양한 가격대 선택지, 할부 옵션 및 혜택 안내|
|나이 ↑ → 소비 ↓| 고령 고객: 휴식 공간 확보, 쉬운 안내, 참여 프로그램, 건강·복지 지원, 접근성 개선 </li></ul>|

Below are the results of clusterisation performed on the data set and comments on each group.
<br>다음은 데이터셋 클러스터링 결과와 각 그룹에 대한 코멘트입니다

| Group | Potential Customer Portrait | Comments|
|:----------|:----------|:----------|
|Budget Savers <br> 12%|Low income, low score|Saving as the main goal <br> Sales, free merch, food tastings, discounts for various social groups <br> Focus on availability and accessibility, potential growth to Steady Shoppers|
|Deal Hunters <br> 11%|Low income, high score|People with enough time and interest to look for various deals and promotions<br> "Hidden" sales, content on saving strategies, short-time promotions, gamefication of shopping experience <br>Potential growth to Steady Shoppers|
|Steady Shoppers <br> 41%|Average income, average score|The largest group of customers <br> Loyalty programs, seasonal deals, regular bonuses <br> Focus on retention and encouragment on more spending|
|High Rollers <br>17%|High income, low score|Personalization, privacy, and exclusiveness<br> VIP service, personal assistants, reservations, and services available through app to save time and ensure convenience|
|Prime Spenders <br> 20%|High income, high score|The most valuable customers <br> VIP service, personal assistants, private locations, exclusive events, early access, premium club members<br>Focus on retention|

|그룹 | 잠재 고객 특징 | 코멘트|
|:----------|:----------|:----------|
|Budget Savers <br> 12%	| 저소득, 낮은 점수 |	절약 중심 고객 <br> 세일, 무료 상품, 시식, 다양한 사회 그룹 할인 <br> 접근성과 가용성 강조, Steady Shoppers로 성장 가능|
|Deal Hunters <br> 11%	|저소득, 높은 점수	|다양한 할인과 프로모션 탐색에 관심과 시간 있음 <br> 숨은 세일, 절약 전략 콘텐츠, 단기 프로모션, 쇼핑 경험 게임화 <br> Steady Shoppers로 성장 가능|
|Steady Shoppers <br> 41% |평균 소득, 평균 점수 | 가장 큰 고객군 <br> 로열티 프로그램, 시즌별 할인, 정기 보너스  <br>유지 및 추가 소비 유도에 집중|
|High Rollers <br> 17%	|고소득, 낮은 점수	| 개인화, 프라이버시, 독점성 강조 <br> VIP 서비스, 개인 어시스턴트, 앱을 통한 예약 및 서비스 제공|
|Prime Spenders <br> 20% |고소득, 높은 점수 | 최상위 가치 고객 <br> VIP 서비스, 개인 어시스턴트, 전용 공간, 독점 이벤트, 얼리 액세스, 프리미엄 클럽 회원 <br> 유지에 집중|

![Bivariate Clustering](https://github.com/rinaguskova/Images/blob/main/clustering_bivaraiate.png)
