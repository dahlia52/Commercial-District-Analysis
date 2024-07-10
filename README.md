# Commercial-District-Analysis

## Project Period
2023.3 ~ 2023.4
<br><br>

## Project Introduction
VARS 모델 기반 광진구 상권분석 & 군집분석 대시보드 개발 및 솔루션 제시
<br><br>

## Background
광진구의 주요 문제는 광진구가 ‘베드타운’인 점에서 파생한다. 문제를 근본적으로 해결하기 위해서는 업무 및 상업 중심지로 발전해야한다.
<br><br>

## Research
VARS 모델 개발
- 기존의 C-READI 모델을 데이터에 적용할 수 있도록 변형한 모델
- 상권의 업종다양성(Variety), 접근성(Access), 임대료(Rent), 생존가능성(Survivalbility)을 측정하는 모델
  - `업종다양성`: 2022년에 매출이 발생한 업종 개수
  - `접근성`: 일정 반경 이내에 정차하는 버스 및 지하철 노선 개수, 버스 정류장 및 지하철역까지의 거리 계산, 보행자우선도로 데이터를 통해 도보 5분 이내에 위치한 보행자우선도로 개수
  - `임대료`: 분기별 임대료 증가율 RMSE
  - `생존가능성`: 신생기업 진출 시 생존가능성
<br>

군집 분석 
- 추정매출 데이터를 통해 상권 유형별로 군집 분석
- 군집 분석 결과 해석 시 해당 군집만의 주업종, 고객 연령대 및 성별 분포, 주 매출 발생 시간대 및 요일 등을 고려함
<br><br>

## Report

[VARS 모델 기반 광진구 상권분석 & 군집분석 대시보드 개발 및 솔루션 제시 보고서](https://github.com/dahlia52/Commercial-District-Analysis/blob/main/%5B%EC%83%81%EA%B6%8C%EC%9D%84%20%EB%B6%80%ED%83%81%ED%95%B4%5D%20VARS%20%EB%AA%A8%EB%8D%B8%20%EA%B8%B0%EB%B0%98%20%EC%83%81%EA%B6%8C%EB%B6%84%EC%84%9D%26%EA%B5%B0%EC%A7%91%EB%B6%84%EC%84%9D%20%EB%8C%80%EC%8B%9C%EB%B3%B4%EB%93%9C%20%EA%B0%9C%EB%B0%9C%20%EB%B0%8F%20%EC%86%94%EB%A3%A8%EC%85%98%20%EC%A0%9C%EC%8B%9C.pdf)

[VARS 모델 기반 대시보드](https://public.tableau.com/app/profile/seeun.lim/viz/_16830084006840/_): VARS 모델 점수를 나타내는 대시보드 개발

