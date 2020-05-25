
	사전 준비	4

  1.	Reference	4
  
    1.1.	Advantech ARK-1123 Gateway	4
    
    1.2.	Advantech WISE-4012 Data Acquisition and protocol converter	4
    
    1.3.	Microsoft Azure Introduce	4
    
    1.4.	Microsoft Azure Portal	4
    
  2.	Requirements	4
    2.1.	Azure account with subscription	4
    2.2.	Microsoft Visual Studio 2017	4
  3.	Goals	4



	실습1 (Gateway + Windows 10)	6

  1.	Device 구성	6
  
    1.1.	전체 디바이스 연결 구성 – 센서 데이터 수집을 위한 환경 구성	6
    
    1.2.	WISE-4012 연결 구성	7
    
    1.3.	온도/습도 센서 연결 구성	7
    
    1.4.	임베디드 PC 연결 구성	8
    
    1.5.	임베디드 PC에 접속	9
    
    1.6.	PC 로그인 정보	9
    
    1.7.	WISE-4012 연결 확인	9
    
    1.8.	AdamApax.NET Utility를 실행	10
    
    1.9.	WISE-4012 장치 인식 확인	10
    
    1.10.	웹브라우저 로그인	11
    
    1.11.	WISE-4012의 동작 상태 확인	11
    

	실습2 (Microsoft Azure Cloud)	12

  1.	Azure Resource 생성	12
  
    1.1.	IoT Hub 생성	12
    
    1.2.	Stream Analytics Job 생성	21
    
    1.3.	COSMOS DB 생성	23
    
  2.	Resource 항목 설정	25
  
    2.1.	Cosmos DB 설정	25
    
    2.2.	Stream Analytics Job 설정	26
    
  3.	각 리소스의 동작 유무 확인	30
  
    3.1.	Stream Analytics 작업 시작	30
    
    3.2.	Cosmos DB 데이터 확인	30
    
  4.	Power BI – Cosmos DB	31
  
    4.1.	Power BI – Cosmos DB 연결	31
    
    4.2.	데이터베이스 쿼리 편집	34
    
    4.3.	Dashboard 위젯 구성	36
    


	Appendix : Azure 연결 확인	37

  1.	Device Explorer 다운로드(GitHub)	37
  
  2.	Device Explorer 설정	37
  
  3.	시뮬레이션 데이터 통신 테스트	39
  
  

	Appendix : UWP 앱 배포	41

  1.	Visual Studio 설치	41
  
    1.1.	Windows 10 개발자 모드로 변경	41
    
    1.2.	사전 설치 - NuGet package	41
    
    1.3.	솔루션 구성	42
    
  2.	UWP 배포	43
  
    2.1.	Debug / x86 / 로컬 컴퓨터 확인 후 실행	43
    
    2.2.	프로그램이 실행되면 Start Reading 옆의 단추를 클릭합니다.	43
    
    

	Appendix	44

  1.	센서의 제어	44
  
    1.1.	Azure Service bus	44
    
    1.2.	Azure Function	44
    
  2.	Azure Learn	44
 
