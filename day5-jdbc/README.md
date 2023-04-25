# 보고서 - jdbc를 사용하여 csv 파일을 db에 insert 후 select 하기

  ## csv 파일
  
  먼저 csv 파일로 영화 데이터들이 담긴 파일을 받았다.
  
  Rank, Genre, Title, Director, Actor 등의 column으로 이루어진 1000개의 영화 데이터로 이루어져 있다.
  
  <img width="700" alt="1" src="https://user-images.githubusercontent.com/55052142/234143398-afda55c2-78b1-4419-bdcb-07be4c790ebe.png">
  
  ## mysql db에 csv 파일 import
  
  mysql 스키마에 movie 테이블을 생성한다. 
  
  스키마의 오른쪽을 클릭한 후 Table Data wizard import를 선택하여 영화 csv파일을 import 한다. 
  
  <img width="683" alt="2" src="https://user-images.githubusercontent.com/55052142/234146506-207681ed-4a6c-4dd3-91d4-9d2767744236.png">
  
  mysql에 csv 파일이 정상적으로 import 된 것을 확인할 수 있다.

 
  ## 인텔리제이 maven으로 프로젝트 생성
  
  인텔리제이를 maven으로 프로젝트 생성 후 mysql db와 연동시킬 준비한다.
  
  view -> tool window -> database로 들어간다.
  
  인텔리제이 화면 오른쪽에 database 창이 생기면 +를 선택하고 mysql을 선택한다.
  
  <img width="380" alt="3" src="https://user-images.githubusercontent.com/55052142/234147125-7401d861-4173-4a53-85ae-971c09eb350e.png">

  인텔리제이에 mysql이 들어간 것을 확인할 수 있다.
  
  ## 데이터를 불러올 수 있는 Dao 클래스 작성
  
  데이터가 잘 연동되었는지 불러올 수 있는 UserDao 클래스를 작성한다.
  
  <img width="716" alt="4" src="https://user-images.githubusercontent.com/55052142/234147362-93b270f7-5bd5-4afa-88e4-5d604c77df93.png">
  
  <img width="284" alt="5" src="https://user-images.githubusercontent.com/55052142/234147440-52b4a404-1b2f-4482-9e34-3fa3414c66b3.png">
  
  insert가 잘 된 것을 확인할 수 있다.
  
  ## select 해보기
  
  <img width="326" alt="6" src="https://user-images.githubusercontent.com/55052142/234147625-1e68ba81-4672-42be-9177-68b1b91c695e.png">

  select문 실행
  
  <img width="1259" alt="7" src="https://user-images.githubusercontent.com/55052142/234147760-a87478be-075e-498b-8984-9505658d2a9e.png">
  
  영화데이터가 잘 실행되는 것을 볼 수 있다. 

  
  


  
  
  
  
  
  
  
  
  
  

  
  

  
