# Dialogflow-Android-Project
Google 챗봇 플랫폼인 Dialogflow와 Android를 연동한 프로젝트

![image](https://user-images.githubusercontent.com/42290273/100836195-37356000-34b2-11eb-928d-dff04dc40b9a.png)


## 기능설명
* ### Speech To Text(STT)
 왼쪽 상단의 버튼 클릭 시 음성인식을 시작하여 음성인식 결과를 dialogflow Agent에 전달.  
 (Response Text에 결과 확인 가능)
* ### Text 입력 
 상단의 editText에 원하는 쿼리를 입력하고 전송 버튼을 누르면 dialogflow Agent에 전달.  
 (Response Text에 결과 확인 가능)
* ### 물어보기 버튼
 저장되어 있는 "오늘 날씨 어때" 요청 문장을 dialogflow Agent로 전달하여 응답 쿼리가 제대로 오는지 테스트하기 위함.  
 (scenario Text에 결과 확인 가능)
* ### 대화하기 버튼
 저장되어 있는 "점심 메뉴 추천해줘","중국집 메뉴 알려줘" 요청 문장을 dialogflow Agent로 전달하여 follow-up Intent의 응답 쿼리가 제대로 오는지 테스트하기 위함.  
 (scenario Text에 결과 확인 가능)
* ### 알람받기 버튼
 타이머를 5초로 세팅해 타이머 종료시 자동으로 정해진 알람 command를 dialogflow Agent로 전달하여 해당하는 응답 쿼리를 받음.  
 (scenario Text에 결과 확인 가능)
* ### 퀴즈하기 버튼
 dialogflow에서 설정한 2개의 Response(한번 더 퀴즈를 물어봄, 퀴즈를 끝마침)에 대하여 알맞게 처리함.
 (scenario Text에 결과 확인 가능)
