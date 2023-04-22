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





   
   


   



   
   
   
   
   

   
