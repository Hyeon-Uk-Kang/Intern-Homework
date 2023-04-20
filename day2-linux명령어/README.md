# 보고서 - linux command 기능과 실습

## 리눅스 명령어 

1. mkdir : 디렉토리를 새로 만드는 명령어 
2. ls : 현재 디렉토리에 있는 내용을 출력한다.

   ls -a : 숨겨진 파일이나 디렉토리도 함께 보여준다.
   
   ls -l : 자세한 내용(권한, 포함된 파일 수, 소유자, 그룹, 파일크기, 수정일자, 파일이름)을 보여준다.
   
   ls -al : a와 l의 기능을 모두 포함한다.
   
   ls -h -al : -h를 붙이면 K, M, G 단위의 파일크기를 사용하여 사람에게 보기 좋게 표시한다.
   
   <img width="567" alt="1" src="https://user-images.githubusercontent.com/55052142/233301318-ede29b48-cb2d-4080-93ff-024a6862468c.png">
   
   
   
 3. mv : 파일이나 디렉토리를 이동하거나, 이름을 변경할 때 사용한다.


    ➜ mv <바꾸기 전 디렉토리 이름> <바꾼 후 디렉토리 이름>         : 상위 디렉토리를 하위 디렉토리로 이동시킨다.
    
    ➜ mv <상위 디렉토리> <하위 디렉토리>                          : 상위 디렉토리를 하위 디렉토리로 이동시킨다.
    
    <img width="509" alt="2" src="https://user-images.githubusercontent.com/55052142/233321628-94220558-7b17-4957-bffa-7e32a92822d1.png">


 
 
 4. cp : 파일이나 디렉토리를 복사하는 명령어 

    ➜ cp <복사하려는 파일/디렉토리 이름> <복사될 파일/디렉토리 이름>
    
    <img width="218" alt="3" src="https://user-images.githubusercontent.com/55052142/233323978-89295891-afdc-4f99-a4a4-0e88611f1684.png">
    
    
    
 5. cat : 파일의 내용을 출력하는 명령어. 파일에 내용을 입력할 때도 사용할 수 있다.

    ➜ cat <출력하려는 파일 이름>
    
    ➜ cat > <내용을 입력하려는 파일 이름>

    <img width="185" alt="4" src="https://user-images.githubusercontent.com/55052142/233394691-9839c818-9308-43f7-b6f9-34adee4f7053.png">
    
 6. chmod : 해당 파일이나 디렉토리의 퍼미션(허용 권한)을 수정할 수 있는 명령어이다. [권한을 설정하려는 파일/디렉토리 이름]의 사용권한을 rwxr-xr-x로 설정

    ➜ r : 읽기 권한
    
    ➜ w : 쓰기 권한
    
    ➜ x : 실행 권한
    
    ➜ - : 권한 없음
    
    <img width="347" alt="5" src="https://user-images.githubusercontent.com/55052142/233412368-4ac8f1ef-a67a-44ea-bbab-04ed020c6c1a.png">
    
    
7. pwd : 현재 디렉토리를 프린트하는 명령어

    <img width="200" alt="6" src="https://user-images.githubusercontent.com/55052142/233416909-c5d6676c-921b-4cf7-bf9e-fb93b8d5eeed.png">
    
8. rm : 파일/디렉토리를 제거하는명령어


    <img width="500" alt="77" src="https://user-images.githubusercontent.com/55052142/233421866-2ca197b2-e062-43ce-823f-9602cfbb1839.png">
    
9. rmdir : 빈 디렉토리를 제거하는 명령어. 다만 디렉토리가 비어있지 않다면 제거할 수 없다.

    <img width="383" alt="8" src="https://user-images.githubusercontent.com/55052142/233435904-14c6e5d1-3376-46f1-b4a5-86862b3740fc.png">









