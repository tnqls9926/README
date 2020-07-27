1주차- 1.Github기초
====================

### 1. repository 생성하기
- new repository로 repository 생성   
(주소는 push할때 사용됨)

### 2. 코드 올리기
자기가 준비해온 코드를 열어준다.   
- 콘솔창
  - 깃허브 커맨드들을 친다.
- Gitbash  
  - 윈도우 사용시
  - 해당 디렉토리가 있는 코드로 이동
  
### 3. 콘솔창에 커맨드 치기
- git init
  - 깃 시작하기
  - 해당폴더(저장소)에 깃파일 만들어짐
  
- git remote add origin 레포지토리 주소
  - 깃이랑 레포지토리 주소url랑 연결하기
  - local(PC)<--->master(Github)
  
- git add .
  - .: 모든걸 추가하겠다는 의미
  - 디렉토리의 파일들이 push전 준비상태로 들어감
  
- git commit -m "원하는 내용"
  - -m: 커밋에대한 설명 적어줌
  - 아직 master로 push되지 않은 상태
  - 파일들을 git이랑 준비하고 있는 상태

- git push origin master
  - 코드 repository로 올림
  - master(repository가있는 서버)로 올림

**수정 시   
git add: 변경된 사항 올림   
git commit -m: 커밋에 대한 설명적    (아직 push되지 않은 상태)   
git push orign master: master에 올림 
