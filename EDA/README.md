# 데이터 변수 종류

- Age (나이)
- Attrition (퇴사 여부) -> target 변수
- BusinessTravel(출장 빈도)
- Daily Rate (회사지출 비용/일)
- Department (부서)
- Distance from Home (집과 회사 간 거리)
- Education (교육수준)
- Education Field (전공 분야)
- Employee Number (직원 고유 번호)
- Environment Satisfation (회사 만족도)
- Gender (성별)
- Hourly Rate(회사 지출 비용 /시간)
- Job involvement (직업 참여도)
- Job Level (직급)
- Job Role (직무 명칭)
- Job Satisfaction (직업 만족도)
- Marital Status (결혼 관계)
- Monthly Income (월급)
- Monthly Rate (회사 지출 비용/월)
- Num Compaies Worked (일해본 회사 수)
- *Over 18 (직원 나이)*
- Overtime (초과근무 여부)
- Percent Salary Hike (월급 상승률)
- Performance Rating (직업 능력 평가)
- Relationship Satisfaction (타 직원들과의 관계 만족도)
- *Standard Hours (표준근무 시간)*
- Stock Option Level (주식 매수 선택권)
- Total Working Years (일한 기간)
- Training Time Last Year (작년 연수 시간)
- Work Life Balance (일과 삶의 균형 정도)
- Years at Company (현 회사 근무 기간)
- Years in Current Role (현 직무 기간)
- Years since last Promotion (마지막 승진 후 현재까지 기간)
- Years with current manager (현 상사와 일한 기간)

# 데이터 변수 분석

1) 개인정보 : Age, Education, Education Field, Gender, Marital Status, Num Compaies Worked, Total Working Years

- 회사인적정보(고정지수) : Employee Number, Training Time Last Year, Years at Company, Years in Current Role, Years since last Promotion

2) 회사의 기회비용 : Daily Rate, Hourly Rate, Monthly Income, Monthly Rate, Stock Option Level, Percent Salary Hike

3) 주변 환경 및 변수: Department, BusinessTravel, Distance from Home, Job Level (1~5),Overtime, Performance Rating, Years with current manager

4) 개인 변수: Environment Satisfation, Job involvement, Job Satisfaction, Relationship Satisfaction, Work Life Balance


# 데이터 변수 설명

## 종속변수(Attrition) : (Y/N)

Department [R & D, Sales, HR]

Distance from Home [1 mile = 1.609344 km]

Education [1:고졸, 2:전문학사, 3:학사, 4:석사, 5:박사]

Education Field [Medical, Other, Marketing]

BusinessTravel [Non-Travel(출장 가지 않음), Travel_Rarely (출장 빈도 낮음), Travel_Frequently (출장 빈도 높음)]

Environment Satisfation (0~4, 4 = Best)

Gender (Male/Female)

Job involvement (0~4, 4 = Best)

Job Level (1~5, 5 = Best)

Job Satisfaction (1~4, 4 = Best)

Marital Status [Divorced(이혼), Married(결혼), Single(비혼)]

Over18 (Y/N)

Performance Rating (직업 능력 평가 1~4)

Relationship Satisfaction (1~4, 4 = Best)

Stock Option Level (0~4, 4 = Best)

Work Life Balance (1~4, 4 = Best)