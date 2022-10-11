# 1. 프로젝트 소개


# 2. 팀 소개
Park Haemi, hmpark042@gmail.com, Unity 개발 및 IMU Fusion 분석

Park Minsu, , BLE를 이용한 센서/Gateway 통신 및  소켓 통신 개발


# 3. 구성도


# 4. 소개 및 시연 영상


# 5. 사용법
본 프로젝트는 Window 환경에서 Motion Capture 디렉토리 안에 있는 MotionCapture.exe 파일을 실행하여 사용할 수 있습니다.

![빌드사진](https://user-images.githubusercontent.com/48706944/195005486-e98a49db-181e-4472-b95d-8328cca30ee1.png)

* 본 프로젝트는 센서 및 게이트웨이 세팅 완료를 요구합니다.
* 입력칸에 IP Address와 Port 번호를 입력한 후 SAVE 버튼을 눌러 게이트웨이 세팅을 변경할 수 있습니다.
* 게이트웨이에서 소켓 서버를 열었다면 Start Streaming 버튼을 클릭합니다.
* 소켓 연결 및 게이트웨이에서 센서를 성공적으로 발견했다면 Sync 버튼을, 발견하지 못했다면 서버를 열고 Stop Streaming을 클릭하고 다시 Start Streaming 버튼을 클릭해 재연결을 시도합니다.
* Sync 버튼을 클릭했다면 T자 자세로 3초간 대기합니다.
* 자세 동기화가 실패했을 경우 Re Sync 버튼을 클릭하여 다시 동기화를 시도합니다.
* 실행 파일을 종료하려면 ESC 키를 누릅니다.
