# Git / Github

<br/>

## **Git과 Github의 차이점**
- git이란 버전 컨트롤러로 총 4가지의 상태(*untracked, modified, stage, committed*)가 있다. 로컬에서 작업한 내용을 저장해준다.


  ** git은 stage area와 repository를 가지고 있다.

   `stage area`는 업로드하기 전 업로드 할 대기파일들이 올라가는 공간. (*add를 통해 작업)* 

   `repository`는 stage area에 있던 파일들이 올라가는 공간. (*최종적으로 올라가는 공간이고, commit을 통해 작업이 된다. )*


- github이란 깃허브에서 제공해주는 클라우드 서버에 local에서 관리한 소스코드를 업로드나 공유할 수 있는 공간이다.


<br/>

- - - 
<br/>

## **init, add, commit -m 명령어들에 대한 설명**
| 명령어 | alias | 설명 |  
|:-----------:|:----------------:|:------------------------:|
| init | g i | git 레파지토리 관리를 시작하도록 한다.(git 저장소를 생성한다.)
| add | ~~add~~ | 디렉토리 상의 변경 내용을 스테이징 영역에 추가한다.
| commit -m | g cm "<*MESSAGE*>" | 커밋을 하여 추가 및 변경된 사항들을 저장소에 기록한다.

** git commit -a -> 스테이징 절차(add)를 생략하고 바로 add와 commit을 동시에 가능.

<br/>

- - - 
<br/>

## **remote, clone, push, pull 명령어들에 대한 설명**
- `remote` : 로컬이 아닌 네트워크 상의 위치에 존재하는 git 저장소
- `clone` : 원격 저장소의 내용을 다운로드하는 것
- `push` : 원격 저장소에 코드 변경부분을 업로드하는 것
- `pull` : 원격 저장소의 변경된 데이터를 가져오는 것

<br/>

- - - 
<br/>

## **사진 첨부하기**

![keyboard cat](https://i.ytimg.com/vi/0nqJKEh3YCc/maxresdefault.jpg)
[사진 url](https://i.ytimg.com/vi/0nqJKEh3YCc/maxresdefault.jpg)

<br/>

- - - 
<br/>

## **branch, checkout 명령어 설명**
### branch :
독립적으로 작업을 진행하기 위하여 사용하는 개념으로, 각각의 브랜치는 다른 브랜치에 영향을 주지 않는다.

### checkout :
자신이 사용할 브랜치를 지정하는 것으로, 명령어는 $ git checkout \<branch> 이다.


<br/>

- - - 
<br/>

## **merge 2가지 설명 (fast-forward/Merge conflict)**
- `fast-forward` : 병합할 브랜치의 커밋이 현재 브랜치의 커밋보다 앞서가 있기 때문에, 기준 브랜치의 커밋을 대상 브랜치 커밋으로 이동하겠다는 의미이다.
- `merge conflict` : 병합할 때 일어나는 충돌이다.

