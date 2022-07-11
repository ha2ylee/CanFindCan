# CanFindCan : 시각장애인을 위한 캔음료 인식 애플리케이션
<br/>

# 💡 프로젝트 소개
- 시각장애인들에게 새로운 소통 방식을 제공하기 위해 애플리케이션을 구현하고자 함
- 점자 표기로는 종류의 구분이 불가능한 캔 음료의 구분에 목적을 둠 
- 카메라로 캔을 비추면 캔의 종류를 분석하고, 캔의 밑바닥을 촬영하면 유통기한을 음성으로 안내

# 💡 프로젝트 구성도
<img src="https://user-images.githubusercontent.com/76219962/178248651-457a1544-27bd-4b8b-ad78-e3e88259544b.png" width="600px" height="300px">
<br/>

# 💡 주요 기능

### 1. 캔 종류 인식
<img src="https://user-images.githubusercontent.com/76219962/178249823-946f9110-bb56-46da-9abc-b69f31f37ab8.png" width="30%" height="30%">

- 애플리케이션 실행 시 자동으로 웹 뷰 실행
- 학습된 데이터가 적용된 HTML 기반의 웹 서버
- 실행된 카메라에 캔을 비추면 종류 분석 진행
- 분석 완료 시 음성 안내


### 2. 유통기한 인식
<img src="https://user-images.githubusercontent.com/76219962/178249319-9c742dfc-53c1-4167-93e8-2030d15e3774.png" width="600px" height="200px">

- 중앙부에 위치한 카메라 버튼 클릭 시 내장 카메라 실행
- 카메라로 캔 바닥 촬영
- 유통기한 글자 추출 후 음성 안내
- 상단 BACK 버튼 클릭 시 캔 음료 인식 기능 재실행

