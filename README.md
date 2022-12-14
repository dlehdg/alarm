<img src="https://capsule-render.vercel.app/api?type=wave&color=auto&height=300&section=header&text=최소%20A+만%20주세요&fontSize=90" />

# 앱 이름 : 알람-나 좀 깨워주세요

전화 연결 등을 통해 일어나고자 할 때 반드시 일어나도록하는 알람앱입니다.

## 개발 동기

누구나 한 번쯤은 알람을 못 들어 일어나야할 시간에 일어나지 못한 경험이 있을 것입니다. 이 알람앱은 이러한 일을 최대한 방지하고자 알람 실패시 지인에게 전화나 문자를 통해 대신 깨워주도록합니다.

# 개발 기획서


## 화면 디자인

각 액티비티에 들어갈 화면 디자인을 구현합니다.

### 화면 디자인 Task

포토샵으로 작업->작업물을 제플린에 올림

제플린 : 디자인->코드로 변환시켜주는 툴

디자인할 화면 : 메인화면, 알람 설정 화면, 메인화면에 추가할 recyclerview 화면
## 메인화면
1. 설정된 알람 설정 시간들을 확인 할 수 있다.
2. 설정된 알람 클릭시 해당 알람을 수정할 수 있다.
3. 전화, 문자연결이 누구에게 되어있는지 확인 할 수 있다. 
4. +버튼 클릭시 알람을 추가할 수 있다.
5. 상단에 오늘의 날씨를 확인 할 수 있다.

### 메인화면 Task

1. 설정 화면에서 알람 추가 시 메인화면에 알람이 추가되는 기능 구현
2. 설정된 알람 클릭 시 설정 화면에서 해당 알람 수정 기능 구현
3. 해당 알림에 전화, 문자연결이 누구에게 되어있는지 보이도록 구현
4. +버튼 클릭시 설정화면에서 알람을 추가할 수 있도록 구현
5. 메인화면 상단에 오늘의 날씨를 확인할 수 있는 위젯 구현
6. 알람을 옆으로 밀어서 손쉽게 삭제 가능(추가)
7. 요일별로 알람을 온오프 할 수 있는 기능(추가)

## 알람 설정 화면

1. 알람이 울릴 시간을 설정한다.
2. 연락처 연결기능
3. 전화, 문자연결 기능
4. 요일 설정 기능
### 알람 설정 화면 Task

1. timepicker를 통해 알람을 설정한다.
2. 버튼 클릭시 연락처 목록을 가져오도록 구현
3. 연결한 연락처로 기상 실패 시 전화나 문자기능을 수행하도록 구현
4. 요일별로 알람이 반복적으로 울리도록 구현한다.

# 데이터 저장 방법
1. room을 활용한 sqlite를 이용하여 알람저장
2. 저장한 내용을 recyclerview를 활용해 메인 화면에 구현
3. 요일별 알림 온오프 기능(boolean 형으로 요일별 온오프 지정)
4. 저장된 내용 삭제

# 추가 할 내용
1. 추가할만한 기능은 뭐가 있는지?.
  - 앞선 메인 기능(알람->전화, 문자 연결)을 우선적으로 구현
  - 알람과 연동할 만한 가벼운 게임?->어떤 게임을 구현할 것인가?

