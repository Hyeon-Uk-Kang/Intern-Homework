# 보고서-WSL을 이용한 리눅스 환경 구성 방법


## WSL이란? 

'Widows Subsystem for Linux'의 앞글자만 딴 것으로, 윈도우 시스템에서 곧바로 리눅스를 실행할 수 있도록 하는 매우 편리한 시스템이다. 장점은 다음과 같다.

1. 윈도우에서 재부팅이나, 또는 가상 프로그램 실행 없이 리눅스 실행
2. 윈도우 탐색기에서 리눅스 읽기 쓰기, 또는 리눅스 환경에서 윈도우 폴더 읽기, 쓰기 모두 가능
3. 리눅스 전용 포맷 (ext4 등) 없이 리눅스 프로그램 실행 가능
4. 리눅스 컴파일러로 코드를 실행, 또는 전용 컴파일러, 프로그램 실행 가능


## 다음은 WSL을 사용하기 위한 요구설정이다.

* window 10 2004 이상
* BIOS 설정에서 가상화 활성화


## WSL 설치

1. 관리자 권한으로 cmd 창을 열고 wsl --install 을 입력한다.

   <img width="310" alt="1" src="https://user-images.githubusercontent.com/55052142/233046982-41fa8a2a-5286-4a88-950a-0511e3e577a5.png">
   
2. 컴퓨터를 재부팅한다.
3. 우분투 환경준비가 시작되면 리눅스에서 사용할 사용자 아이디와 비밀번호를 입력한다. 
   
   <img width="600" alt="2" src="https://user-images.githubusercontent.com/55052142/233083241-524d16a3-f8ac-4922-a97e-4fa0600e84e2.png">
   
 4. 다시 관리자 권한으로 cmd 창을 열고 wsl -l -v 을 입력하여 잘 설치되었는지 확인한다.
 
      <img width="303" alt="3" src="https://user-images.githubusercontent.com/55052142/233085006-966282c5-44e3-4901-9438-a0060195f682.png">

