# 🏕️ CampShare
## 목차
| 순번 | 목차 항목 |
| :-: | :-: |
| 1 | [팀원 소개](#팀원-소개) |
| 2 | [프로젝트 기간](#프로젝트-기간) |
| 3 | [추진 배경](#추진-배경) |
| 4 | [프로젝트 목표](#프로젝트-목표) |
| 5 | [시스템 설계도](#시스템-설계도) |
| 6 | [프로젝트 요약](#프로젝트-요약) |
| 6.1 | [추가 자료](#추가-자료) |

## 팀원 소개

| _이름_ | 노영준 | 김정현 | 김승범 | 정규원 | 최재우 | 함상억 |
|:-----:|:----:|:-----:|:----:|:----:|:-----:|:----:|
| ___역할___ | 멘토 | AI | BE, Crawling | FE, BE, Crawling | BE | FE |
| ___Github___ | <a href="https://github.com/youngjun-99"><img src="https://avatars.githubusercontent.com/u/83204523?v=4" width="64" height="64"></a> | <a href="https://github.com/kjhz2"><img src="https://avatars.githubusercontent.com/u/146512830?v=4" width="64" height="64"></a> | <a href="https://github.com/SeungBeom53"><img src="https://avatars.githubusercontent.com/u/132819503?v=4" width="64" height="64"></a> | <a href="https://github.com/digitpic"><img src="https://avatars.githubusercontent.com/u/63178849?v=4" width="64" height="64"></a> | <a href="https://github.com/cjw0324"><img src="https://avatars.githubusercontent.com/u/51539046?v=4" width="64" height="64"></a> | <a href="https://github.com/Sangeok"><img src="https://avatars.githubusercontent.com/u/103489700?v=4" width="64" height="64"></a> |

## 프로젝트 기간
- 23.09 ~ 23.12

## 추진 배경
<img width="1017" alt="가격부담,활용도" src="https://github.com/TABA4-9/.github/assets/63178849/1e834b7e-1850-4668-b50c-678f3e97aaab"><br>
- 캠핑 이용자들의 1년 이내 '캠핑 횟수'가 평균 5.5회, '숙박 일수'는 평균 1.3일로 조사 됨<br>
- 1년 중 단 2%만 캠핑 용품을 사용하고 있음을 확인<br>
- 캠핑 용품들은 1년의 98%만큼이나 사용 중이지 않는 상태로 방치되어지고 있음을 확인<br>
- 현재 고가의 캠핑 장비들이 제 가치를 못하고 있다고 판단, 이를 활용해 가치를 창출하고자 함

> 참고자료: https://www.alioplus.go.kr/news/newsDetail.do;jsessionid=d-VW2eUDsJ1Xy9w2m55EQRt5.node21?brdSeq=19563
  
## 프로젝트 목표
- 캠핑용품 제공자는 캠핑용품 대여자에게 캠핑용품을 대여해줌으로써 일정 비용을 제공받을 수 있게 함
- 캠핑용품 대여자는 가격이 비싼 캠핑용품을 대여함으로써 캠핑 활동을 즐길 수 있게 하거나, 관심이 있는 캠핑용품을 구매하기 전에 체험 해볼 수 있게 함

## 시스템 설계도
<img width="883" alt="시스템 설계도" src="https://github.com/TABA4-9/.github/assets/63178849/d25041d4-b9e8-4ed3-8838-741d457d5824"><br>

## 프로젝트 요약

|번호|항목|내용|비고|
|:-:|:-:|:-:|:-:|
|1|문제<br>(Problem)|1. 코로나19로 인한 캠핑 수요 증가<br>2. 캠핑의 지속적인 수요 증가에 따른 캠핑용품 가격 상승<br>3. 물품 필요자의 캠핑 용품에 대한 가격 부담<br>4. 물품 제공자의 낮은 물품 활용성|
|2|가치 제안<br>(Unique Value Proposition)|물품 제공자는 물품을 대여해줌으로써 수익 창출이 가능하며,<br>물품 필요자는 구매에 대한 가격 부담 없이 캠핑 용품 경험이 가능|
|3|솔루션<br>(Solution)|1. 캠핑 용품에 대한 공유 서비스 제공<br>2. 크롤링을 통한 물품 대여 적정 시세 시스템 구축<br>3. AI를 활용한 캠핑 용품 추천 시스템 구현|[AI]<br>1. 유저 활동 기반 품목 추천<br>2. 가격대에 맞는 용품 추천<br>[크롤링]<br>데이터 수집 및 처리|
|4|핵심 지표<br>(Key Metrics)|서비스 내 물품 필요자와 물품 제공자의 일일 매칭 횟수|
|5|경쟁 우위<br>(Unfair Advantage)|다른 캠핑 용품 대여 업체와 달리 캠핑 용품 추천 AI 활용|
|6|채널<br>(Channels)|웹사이트(React + Spring Boot + Tibero6 + AWS)|
|7|고객 세그먼트<br>(Customer Segments)|1. 부담스러운 캠핑 용품 가격으로 캠핑을 시작하지 못하는 사용자<br>2. 캠핑 용품을 자주 활용하지 못해 대여를 통한 수익 창출을 원하는 물품 제공자|
|8|비용 구조<br>(Cost Structure)|1. 기술 개발 및 유지 보수 비용<br>2. 데이터 크롤링 및 처리 비용<br>3. 인건비|
|9|수익 흐름<br>(Revenue Streams)|1. 물품 제공자와 물품 대여자 중개 서비스에 대한 건당 수수료 (%)<br>2. 월간 구독료, 프리미엄 가입<br>3. 광고비<br>4. 캠핑 용품 업계 협업|프리미엄 사용자에게 추가 혜택 제공<br>ex. 건당 수수료 면제|

## 추가 자료
|제목|이미지|
|:-:|:-:|
|캠핑 규모|<img width="1020" alt="캠핑시장규모" src="https://github.com/TABA4-9/.github/assets/63178849/cacb0d06-c449-4e1f-a619-cbd9d58d6245">|
|AI 활용|<img width="1021" alt="AI상품추천" src="https://github.com/TABA4-9/.github/assets/63178849/868fcbbe-920f-4cd1-92c6-f0d4a08674b1">|
