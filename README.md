# Main_Project
### "속초,고성 전기차 충전소 입지 선정 프로젝트"

## 프로젝트 기간
2021년 11월 22일 ~ 2021년 12월 10일 (총 3주)

## 팀원
선명한, 손희서, 유병철, 임지인, 정다예, 조민수

## 참고 프로젝트
(광양시)전기자동차 충전소 최적입지 선정
https://compas.lh.or.kr/subj/past/info?subjNo=SBJ_2009_001

## 설치 모듈
- geopandas (https://geopandas.org/en/stable/index.html)
- folium (https://python-visualization.github.io/folium/)
- tensorflow (https://www.tensorflow.org/?hl=ko)
- pydeck(https://deckgl.readthedocs.io/en/latest/)

## 분석 배경
- 전기차 시장의 증가 상황(현재 13만 4962대 -> 2030년 300만대로 10년뒤 22배 이상으로 전망)

- 주요 전기차 이용 방해요소로 "충전소 부족" 문제

- 공공에서 설치하는 충전소의 경우 수요가 많은 지역을 분석하여 추가 설치하여야 하며 전기자동차 보급 대수와 교통량을 반영한 수요분석이 필요

### "방문객 수요와 교통량을 고려한 급속 충전소의 입지 선정"

- 속초 / 고성을 선정한 이유

- 50기의 급속 충전소를 결정한 분석 배경


## 분석 내용

- 급속 충전소 설치 가능 장소
- 교통량
- 혼잡시간/빈도 강도
- 관광/상권 정보
- 유동인구분포
- 기존 충전소 설치현황 장소


## 모델링
### Maximal Covering Location Problem(MCLP)
(https://github.com/cyang-kth/maximum-coverage-location)

<img src="https://user-images.githubusercontent.com/89237880/152676985-24b13841-718c-472d-a05c-131e21fa058f.png" width="200" height="200"/>

- MCLP는 최대지역커버문제로 Mixed Integer Linear Programming 문제

- 단위 설비 cover demand의 합을 최대화 하면서 K개 설비를 세울 위치를 선정하는 문제

## 결과
### 발표자료 참고
