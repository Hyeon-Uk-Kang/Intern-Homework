# 보고서 - JAVA문법

## 반복문 - for문, while문

   for문은 시작하는 수, 끝나는 수, 증가하는 순으로 작성하며 여러번 반복할 때 사용한다. 
   
   <img width="332" alt="1" src="https://user-images.githubusercontent.com/55052142/233767901-c24a498d-c206-47fa-b283-4b74b1ccbd70.png">
   
   ➜결과
   
   <img width="322" alt="2" src="https://user-images.githubusercontent.com/55052142/233767979-7c99e359-7aac-4fe0-8818-faef97d3f957.png">
   
   
   
   while문은 시작하는 수를 먼저 선언하고, 끝나는 수를 while 옆에 작성한다. 증가는 while 문 안에서 처리한다. 
   
   <img width="336" alt="5" src="https://user-images.githubusercontent.com/55052142/233768442-85824f49-66f5-4fdc-a407-226fccce817a.png">

   ➜결과

   <img width="256" alt="6" src="https://user-images.githubusercontent.com/55052142/233768466-284a3ba5-306f-49de-959a-140bc45a2515.png">

## 중첩반복문

   for문을 여러 개 사용하며 가장 안에 있는 반복문이 먼저 다 실행하게 된다. 
   
   <img width="415" alt="3" src="https://user-images.githubusercontent.com/55052142/233768224-17b8a242-d7af-4357-8124-63a3683d715f.png">

   ➜결과
   
   <img width="311" alt="4" src="https://user-images.githubusercontent.com/55052142/233768236-dc2387ce-51f2-4b37-b404-1557cd50f881.png">
   
   
## 배열

   배열은 저장하는 용도이다. 
   
   작성법은 int [] num={1,2,3,4,5}; 
   라고 한다면 1,2,3,4,5가 순서대로 num이라는 배열에 담긴다. 
   
   <img width="356" alt="7" src="https://user-images.githubusercontent.com/55052142/233769243-1daaef3e-2665-4c78-a354-d15d8e17ea40.png">
   
   ➜결과
   
   <img width="194" alt="8" src="https://user-images.githubusercontent.com/55052142/233769406-4dd0debd-a39b-450b-b938-eaa3b9cee82c.png">
   
   
   배열을 몇 개를 선언할 것인지 만들 수도 있다.
   
   int [] num=new int [3];
   라고 하면 3개의 공간을 만든다.
   그리고 이후에 들어갈 수를 직접 작성한다.
   
   <img width="338" alt="9" src="https://user-images.githubusercontent.com/55052142/233769725-201e24dd-7065-43e6-8707-49e2a19836d2.png">
   
   ➜결과
   
   <img width="204" alt="10" src="https://user-images.githubusercontent.com/55052142/233769764-d7407c68-69d9-4981-bc02-5a074912d31c.png">


## 예외 처리

   예외(Exception)은 프로그래머가 직접 예측 가능하여 막을 수 있는 오류이다. 
   
   try, catch, finally를 사용해 예외를 처리하거나 메소드를 호출한 곳으로 던질 수 있다.
   
   
   ### try, catch
   
   try 문안의 수행할 문장들에서 예외가 발생하지 않는다면 catch문에 속한 문장들은 수행되지 않는다. 하지만 try 문안의 문장을 수행하는 도중에 예외가 발생하면 예외에 해당되는 catch문이    수행된다.
   
   <img width="334" alt="1" src="https://user-images.githubusercontent.com/55052142/233773016-f52c1f36-04f1-484a-9414-e5b71afe2335.png">
   
   ### finally
   
   finally 구문은 try 문장 수행 중 예외발생 여부에 상관없이 무조건 실행시켜야 할 때 사용한다. 
   
   <img width="373" alt="2" src="https://user-images.githubusercontent.com/55052142/233773528-3d015746-c5bd-4101-8d2b-5c39881e2167.png">
   
   ➜결과
   
   <img width="335" alt="2" src="https://user-images.githubusercontent.com/55052142/233773606-ec0c8619-4b95-445b-aedf-e210033c68ad.png">

   
   ### RuntimeException 과 Exception
   
   RuntimeException은 실행시 발생하는 예외이고 Exception은 컴파일시 발생하는 예외이다. 즉, Exception은 프로그램 작성시 이미 예측가능한 예외를 작성할 때 사용하고 
   RuntimeException은 발생 할수도 발생 안 할수도 있는 경우에 작성한다.
   
   <img width="393" alt="1" src="https://user-images.githubusercontent.com/55052142/233774999-673a4bae-42ea-4005-975c-00ebbc8de8d2.png">

   ➜결과
   
   <img width="347" alt="2" src="https://user-images.githubusercontent.com/55052142/233775019-549e6ace-9a35-4aa1-aa22-6fed88c52b7d.png">
   
   런타임오류가 발생했다. Exception으로 변경하면 컴파일 오류가 발생할 것이고, try-catch문으로 처리할 수 있다.
   
   ➜수정 결과
   
   <img width="422" alt="1" src="https://user-images.githubusercontent.com/55052142/233775581-daea51e3-0293-4b75-b9ee-0c905f5156de.png">
   
   
   <img width="271" alt="2" src="https://user-images.githubusercontent.com/55052142/233775644-d819556b-91e5-4883-b55c-090dae1b0107.png">
   
   
## 클래스

   자바에서 클래스(class)란 객체를 정의하는 틀 또는 설계도와 같은 의미로 사용된다.

   자바에서는 이러한 설계도인 클래스를 가지고, 여러 객체를 생성하여 사용한다.


   클래스는 객체의 상태를 나타내는 필드(field)와 객체의 행동을 나타내는 메소드(method)로 구성된다.

   즉, 필드(field)란 클래스에 포함된 변수(variable)를 의미한다.

   또한, 메소드(method)란 어떠한 특정 작업을 수행하기 위한 명령문의 집합이다.
   
   
## 상속

   상속은 자식 클래스가 부모 클래스의 기능을 그대로 물려받는 기능이다. 
   
   상속을 사용하는 이유는 더 빠르고 유지 보수하기 쉽고, 중복이 적고, 통일성이 있기 때문이다. 
   
   <img width="358" alt="1" src="https://user-images.githubusercontent.com/55052142/233823111-9cc3ba3e-2c4d-4bea-a566-908cd6d73fe5.png">
   
   클래스 상속을 위해서는 extends 라는 키워드를 사용한다. 이제 Dog 클래스는 Animal 클래스를 상속하게 되었다. Dog 클래스에 name 이라는 객체변수와 setName 이라는 메서드를 만들지 않    았지만 Animal 클래스를 상속했기 때문에 그대로 사용이 가능하다.
   
   Dog 클래스에 sleep메소드를 추가하였다. 이렇듯 보통 부모 클래스를 상속받은 자식 클래스는 부모 클래스의 기능에 더하여 좀 더 많은 기능을 갖도록 작성한다.
   
   <img width="373" alt="2" src="https://user-images.githubusercontent.com/55052142/233823763-e45cfb97-4325-4937-8eeb-8dc799810884.png">
   
   ### 오버라이딩
   
   오버라이딩(overriding)이란 상속 관계에 있는 부모 클래스에서 이미 정의된 메소드를 자식 클래스에서 같은 시그니쳐를 갖는 메소드로 다시 정의하는 것이다.
   
   <img width="382" alt="3" src="https://user-images.githubusercontent.com/55052142/233826875-db9877b3-893a-48d4-8cbe-3925a6a87462.png">
   
   sleep 메소드가 Dog 클래스가 아닌 HouseDog 클래스에 있는 것에서 출력되는 것을 확인 할 수 있다.
   
   ### 오버로딩
   
   이미 같은 이름의 메소드가 존재하여도 입력항목의 자료형이 다르다면 메소드를 작성할 수 있다. 
   
   <img width="500" alt="4" src="https://user-images.githubusercontent.com/55052142/233827495-5ebbf317-c323-4c2a-9efa-198070a6ad2d.png">

## 추상클래스

   추상클래스는 실체클래스의 공통적인 부분을 추출해 어느정도 규격을 잡아놓은 추상적인 클래스이다. 그래서 실체클래스는 실제 객체를 생성할 정도의 구체성을 가지는 반면 추상클래스는 아    직 메소드와 내용이 추상적이기 떄문에 객체를 생성할 수 없게 만들었다. 추상클래스와 실체클래스는 상속 관계에 있다. 
   
   추상클래스는 공통된 필드와 메서드를 통일할 목적으로 사용한다. 또한 구현시 시간을 절약할 수 있고, 규격에 맞게 사용할 수 있는 장점이 있다. 
   
   <img width="429" alt="1" src="https://user-images.githubusercontent.com/55052142/233830278-5912788c-08e3-4a11-a940-f1b6728d3b63.png">

   
## 인터페이스

   자바에서 인터페이스는 클래스들이 필수로 구현해야 하는 추상 자료형이다. 객체의 사용방법 가이드라인을 제공한다. 자바의 인터페이스는 추상 메서드와 상수로만 이루어져 있다. 구현된 코    드가 없기 때문에 당연히 인터페이스로 인스턴스도 사용할 수 없다.
   
   인터페이스 특징
   
   * 인터페이스에는 구현 소스를 생성할 수 없다. 고로 상수와 추상 메서드만 가질 수 있다.
   * 인터페이스 객체가 아니므로 생성자를 사용할 수 없다.
   * 자식클래스는 부모 인터페이스의 추상 메서드를 모두 오버라이딩해야 한다.
   
   <img width="387" alt="2" src="https://user-images.githubusercontent.com/55052142/233830195-9c3c3321-03c2-44ea-aa59-be8ebdd23644.png">
   
   * 인터페이스는 implements를 사용하여 인터페이스에 정의된 메소드를 각 클래스의 목적에 맞게 기능을 구현하고, 추상 클래스는 extends를 사용하여 자신의 기능들을 하위 클래스로 확장        시킨다.









   
   


   



   
   
   
   
   

   
