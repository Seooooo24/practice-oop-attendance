## Model

### Domain

- Attendance: crew, datetime 속성을 가진다.
- Attendances: 한 크루의 모든 출석 기록 리스트를 저장하는 일급 컬렉션
- Status: 출석, 지각, 결석 횟수를 저장하는 enum. 제적 대상자, 면담 대상자, 경고 대상자를
- Crew: nickName 속성을 가진다. 
- ExpulsionRiskPeople: 제적 위험자 리스트를 저장하는 일급 컬렉션

### Service

- AttendanceService: csv 파일에 직접 접근하는 역할

## Controller

- AttendanceController: 전체 프로그램 컨트롤러

### DTO

- DateDto: 해당 날짜 관련 속성을 담는 DTO


## View

- InputView: 입력값을 받을 때 사용하는 뷰
- OutputView: 출력값을 사용자에게 보여줄 때 사용하는 뷰


