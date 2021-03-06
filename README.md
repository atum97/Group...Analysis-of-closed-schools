# Title
* 미활용 폐교의 최적 활용방안 도출

# Analysis period
* 2021년 8월 2일 ~ 8월 31일 
* 7인 1조의 팀단위 프로젝트

# Purpose
* 전국 폐교의 증감 추세를 확인하고 현황분석을 통해 활용방안들을 카테고리화 하고, 이를통해 각각의 폐교 별 최적의 재활용 방안을 제시할 수 있다.

# My own rules in team
* 데이터 탐색
* 전처리 (법정동 코드 라벨링)
* 현황분석 EDA
* EDA를 통한 분석방향 제시 및 토의
* 상관분석 히트맵

# Analysis method
1. 법률상에 기재되어있는 폐교 활용 방안들(ex. 체육시설, 교육시설 등)을 각각의 카테고리로써 나눈다
2. 각각의 카테고리를 종속변수로 두고 독립변수들의 영향력을 측정한다 \
(ex) 부지면적 x~x, 주변 거주인원 연령대 등등이 체육시설에 미치는 영향 
3. 테스트 / 훈련데이터를 나누고, 지도학습으로써 훈련데이터의 예측결과를 테스트데이터에 대입하여 모델링을 한다
4. 만들어진 모델은 현재 폐교를 다양한 요인들을 바탕으로 어떤식으로 활용하면 좋을 지 추천해준
