# 국제 관계 지수 
"국제 관계 지수" 프로젝트의 저장소 입니다. "국제 관계 지수" 프로젝트는 6단계로 이루어집니다. 

1. 국가간의 관계를 담은 13개국 영문 언론의 기사를 웹크롤러로 수집합니다.
2. 수집한 자료를 데이터베이스 저장하고 API로 제공합니다.
3. BERT 모델을 활용하여 기사를 짧은 문단으로 요약합니다. 
4. Amazon Mturk를 이용, 문단에 나타난 두 국가의 관계(긍정적/부정적)를 라벨링하여 지수화 합니다.
5. 시기별 국가간 관계의 변화를 베이즈 위계 시계열 통계 모델에 따라 추정합니다. 
6. 통계 분석의 결과를 웹사이트의 형태로 공개합니다. 

1과 3과 4의 단계에서는 웹스크롤링, 자연어처리, ML/DL 관련 코드를 살펴보실 수 있습니다. 2와 6의 단계에서는 FE/BE 관련 코드를 살펴보실 수 있습니다. 5의 단계에서는 베이즈 통계와 시계열 통계, 시각화 관련 코드를 살펴보실 수 있습니다.

## 1. 기사 웹크롤링
## 2. 데이터 베이스 정리/ API 제공
## 3. BERT 모델를 활용한 기사 요약
## 4. Amazon Mturk를 이용한 라벨링 자료 확보
## 5. 베이즈 시계열 통계분석
## 6. 시각화 및 웹사이트
