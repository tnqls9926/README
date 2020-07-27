Github 협업
===========

## 자주쓰는 Git 명령어_1
> * git init   
git 저장소를 초기화

> * git add.   
폴더내의 변경된 모든 파일 staging area에 올리기

> * git commit -m "커밋에 대한 설명"   
유사시 돌아갈 수 있는 저장소의 *체크포인트 생성*

> * git remote add origin http://원격 저장소 주소. git   
원격 저장소(remote repository)연결   
원격 저장소와 로컬 저장소 연결

  + 정리    
>  git init   
> : 비어있는 '로컬 git 저장소' 만듦   
>  
>  git add   
>  : staging area에 올림
>  
>  git commit   
>  : local repository에 올림    
> 여기까지는 로컬 저장소에 해당
-------------------------------
> git remote add origin http://원격 저장소 주소. git
> : 클라우드랑 로컬을 연결
-------------------------------

## 자주쓰는 Git 명령어_2
> * git branch 브랜치명   
>   * 새로운 브랜치 생성
>   * branch: 한 리포지토리 내에서 **용도에따라 저장소를 나누는 것** 
>   * 같이 협업할때 이용 됨
> * git checkout 브랜치명
>   * 해당 브랜치로 이동
> * git push origin 브랜치
>   * 원격 저장소의 특정 브랜치에 프로젝트 저장
> * git pull origin 브랜치
>   * 원격 저장소의 특정 브랜치에서 변경사항 pull 해오기
> * git clone http://원격 저장소 주소.git
>   * 원격 저장소에 있는 파일 전체 복사
> * git status
>   * git 저장소의 상태 확인
 
## Github를 사용한 협업
1. repository 만들기   

2. 팀원 추가하기   
  setting - Manage access 
  
3. 초기 프로젝트 push   

4. 팀원들의 로컬에 프로젝트 pull    
  git clone 레포 url      
  --> 초기코드 다운   
  
5. git branch 이름   
  git branch : branch 확인   
  git checkout '이름' : '이름'브랜치로 전환   
  git push orign 이름 : 이름 브렌치에 push   

6. pull request    
  Master랑 merg 하기전 pull request   
  pull request: 나 이거 고쳤는데 한번 봐주세요! 할때   
  base--> 어디에 적용할건지   
  compare --> base로 옮길 것    
  
---------------------------------
* collaborater가 아닌 상태에서 이용할 때
**fork**하기
1. fork 버튼 누르기__ github 페이지
2. 자기 로컬에서 작업하기__ cmd창
  * git clone 주소   
  
