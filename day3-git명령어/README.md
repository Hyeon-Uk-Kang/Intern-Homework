# 보고서 - git command 기능과 실습

## git 특징
git의 기본 기능은 이력 관리이다. git은 전체 소스파일을 대상으로 undo 와 redo 뿐 아니라 협업에 필요한 다양한 기능을 가지고 있다. 또한 빠르고 분산 관리를 할 수 있다.

## git init - 저장소 만들기 

 1. sample 디렉토리 생성
 2. red, orange 파일 만들기
 3. sample 디렉토리를 로컬 저장소로 설정

    <img width="359" alt="1" src="https://user-images.githubusercontent.com/55052142/233591496-f934d940-6bff-4a04-9e86-021cdad9ca8f.png">
    
   
   ➜결과
   
    * sample 디렉토리에 Git 저장소 생성
    * 디렉토리 하위에 .git 디렉토리 생성 - Git과 관련된 정보 저장
    * 쉘 프롬프트가 ➜ sample에서 ➜ sample git:(main) ✗로 변경
    
## git status - 현재 상태 확인

 1. git status 입력

    <img width="425" alt="2" src="https://user-images.githubusercontent.com/55052142/233592714-437acd6b-f332-47eb-ae88-06d6737636f4.png">
    
    
   ➜결과
    
   * 현재 브랜치(main)와 커밋 상태, 작업 중인 파일의 상태 확인
   * untracked files(추적하지 않는 파일)이 존재하는 것을 확인

## git add - 현재 상태 추적

 1. 파일의 변경사항을 인덱스에 추가한다. Git은 커밋하기 전 인덱스에 먼저 커밋할 파일을 추가한다.
 2. git add -A 
 3. git status

     <img width="446" alt="3" src="https://user-images.githubusercontent.com/55052142/233594117-5d8ad329-320e-46be-b2fe-4e54ace77449.png">

## git commit - 현재 상태 저장

 1. 인덱스에 추가된 변경 사항을 저장한다.
 2. -m 옵션을 이용하여 첫 번째 이력에 대한 메시지를 작성한다. 
 
 
    <img width="400" alt="4" src="https://user-images.githubusercontent.com/55052142/233598671-fffea6f7-3347-43c5-860b-b32c6223b608.png">
    
   ➜결과
     
     * 커밋 생성
     
## 새 파일 추가하고 커밋하기

 1. yellow 파일 생성
 2. 상태 확인
 3. 직전 커밋 이후 변경된 전체 파일을 인덱스에 추가

    <img width="445" alt="4" src="https://user-images.githubusercontent.com/55052142/233603062-edf14e71-61b8-4e8b-9d41-ee43ffa8414b.png">


## 추가, 수정, 삭제

 1. red 삭제
 2. orange에 내용 추가
 3. green 파일 추가
 4. 상태 확인
 5. 전체 파일 인덱스에 추가
 6. 세 번째 이력 커밋

    <img width="445" alt="5" src="https://user-images.githubusercontent.com/55052142/233604257-e2d75938-a6b5-49f8-ad8b-7b8d2cf1e7ef.png">
    
  
  ➜결과
   
   * orange를 수정했고 red는 삭제, green은 새로 만들어진 것을 확인



## git log 확인

 1. 전체 로그를 확인한다.

     <img width="500" alt="6" src="https://user-images.githubusercontent.com/55052142/233605716-b8cf96f1-39d6-4eee-9a4a-25d03e907944.png">
     
     
     
## git reset - 이전 상태로(제거)

  1. 특정 커밋까지 이력을 초기화한다. 바로 전, 또는 n번 전까지 작업했던 내용을 취소할 수 있다.
  2. git log를 사용하여 2번 커밋까지 조회한다.
  3. 2번 커밋까지 초기화한다.


     <img width="364" alt="6" src="https://user-images.githubusercontent.com/55052142/233607772-48fbec16-d54e-4d0c-baa6-5ff952a1efff.png">

  ➜결과
   
    * 2번 커밋까지 이력이 초기화된다. 결론적으로 3번 이력 삭제 
    * 지웠던 red가 되살아나고 orange 내용이 수정되고 green 파일이 사라진 것을 확인

## git revert - 이전 상태로(유지)

  1. 특정 커밋을 취소하는 새로운 커밋 
  2. 원상태로 복원한다.

  

   



    
    
