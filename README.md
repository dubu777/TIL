# Markdown
   
> 텍스트 기반의 가벼운 마크업 언어

> 문서의 구조와 내용을 같이 쉽고 빠르게 적고자 탄생
    
    1. # 헤딩 
    2. 순서가 있는 리스트 ==> 1.2.3. 
    3. 순서 없는 리스트 ==> - , * 
    4. 코드블럭 ==> ``` ``` 일반 텍스트와 다르게 코드를 이쁘게 출력
    5. 링크link [title](url)   
        예: [Google](https://google.com, "google link")
    6. 이미지  ![Alt text](url)
    7. 택스트 강조 ** ** 볼드 ** 이태릭
    8.  수평선 --- 가로로 긴

# Git/Github

> 프로젝트에 대한 설명 문서
> GITHUB 프로젝트에서 가장 먼저 보는 문서

> 일반적으로 소프르웨어와 함께 배포 
> 작성 형식은 따로 없으나 일반적으로 마크다운을 이용해 작성



> git init 명령어로 로컬 저장소를 생성, 저장소를 초기화한다.
> github에서 clone이나 download로 directory를 생성한경우 gitinit을 할 필요가 없다. 이미 git에서 관리하겠다고 선언 한것이기 때문에!
> .git(앞에 점 숨긴파일) 디렉토리에 버전관리에 필요한 모든 것이 들어있음


Working Directory : 내가 작업하고 있는 프로젝트의 디렉토리
Staging Area : 커밋을 하기 위해 $ git add 명령어로 추가한 파일들이 모여있는 공간
Repository : 커밋들이 모여있는 저장소



<h2>GITHUB에 commit 하는 순서</h2>
1. 내 github에 repository를 생성한다
2. code를 눌러서 colne or download 버튼을 클릭해서 https url을 복사한다
     git clone https://github.com/dubu777/git_test.git (주소)
    변경사항까지 받아옴
    
    변경사항은 필요없고 결과물만 받고 싶은경우
    download zip을 받아서 하면됨
    
3. git remote add origin 원격 저장소 url ==> 내걸 어디 원격 저장소와 연결할지 정함
    git remote -v 연결이 되어있는지 확인
4. git add README.md ===> staging area에 올리고
5. git commit -m "제목 README.md" ===> repository에 커밋하고
6. git push origin main ===> git을 원격 저장소에 올림!!
git status ===>현재 상태를 볼수있음
