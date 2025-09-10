산곡고 1학년들의 소중한 설문데이터 및 데이터 실습을 위한 csv모음

<Student_performance_data 파일 설명>_data from kaggle_"https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset"

🆔 학생 ID
StudentID: 각 학생에게 부여된 고유 번호 (1001번부터 3392번까지).

👤 인구통계 정보
Age(나이): 학생들의 나이는 15세에서 18세 사이.
Gender(성별): 0은 남학생, 1은 여학생.
Ethnicity(인종/민족): 숫자로 구분됨
0: 백인
1: 아프리카계 미국인
2: 아시아인
3: 기타
ParentalEducation(부모 학력 수준):
0: 없음
1: 고등학교
2: 대학교 중퇴(일부 수강)
3: 학사 학위
4: 석사 이상

📚 학습 습관
StudyTimeWeekly(주간 학습 시간): 주당 공부 시간(0시간 ~ 20시간).
Absences(결석 횟수): 학기 중 결석 횟수(0회 ~ 30회).
Tutoring(과외 여부): 0은 없음, 1은 있음.

👨‍👩‍👧 부모 참여
ParentalSupport(부모 지원 정도):
0: 없음
1: 낮음
2: 보통
3: 높음
4: 매우 높음

🎭 비교과 활동
Extracurricular(비교과 활동 참여): 0은 없음, 1은 있음.
Sports(스포츠 활동 참여): 0은 없음, 1은 있음.
Music(음악 활동 참여): 0은 없음, 1은 있음.
Volunteering(봉사 활동 참여): 0은 없음, 1은 있음.

📖 학업 성취
GPA(평점 평균): 2.0 ~ 4.0 사이.
학습 습관, 부모의 지원, 비교과 활동에 영향을 받음.
Target Variable: Grade Class(성적 등급 변수)
GPA를 기준으로 학생 성적을 등급화한 값.
0: A (GPA ≥ 3.5)
1: B (3.0 ≤ GPA < 3.5)
2: C (2.5 ≤ GPA < 3.0)
3: D (2.0 ≤ GPA < 2.5)
4: F (GPA < 2.0)
