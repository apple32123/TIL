#  Git Basic 01

## 1. 설치

###  1) git-bash 

	####    - https://git-scm.com/download/win에 접속 후 "**[64-bit Git for Windows Setup]**" 설치

###   2) Visual Studio Code

 	####     - https://code.visualstudio.com/docs/?dv=win 링크 접속시 자동 설치 (기타 항목 체모두 체크)

 ###   3) Typora

 ####   - https://typora.io/releases/all 에 접속 후 "Dev/Beta Releases" 클릭 후 컴퓨터 사항에 맞는 프로그램 설치





## 2. Git Bash

- Linux 기반으로 명령어를 통해 다양한 동작 실행 (Git Bash = 키보드, 터미널 이용 )
-  "~"는 실행 위치
  - 명령어
    - cd ..
      - 상위 폴더로 이동
    - touch "파일이름".파일형식(txt, pptx, exe ...)
      - 파일 형식에 따른 파일생성
    - ls 
      - 위치 안에 항목 표시
      - ls -a 는 숨김파일 모두 표시

​	

## 필요한 명령어

```python
$git init

$touch README.md

$git add README.md

$git config --global user.name "이름"

$git config --global user.email 'mail'

$cat ~/.gitfonfig      =>입력한 대로 잘 나오는지 확인

$git commit -m 'first commit' 
```



## 순서

```python
$git add "메이크업"
$git commit -m 'first commit'      -> 스테이징	
```







## NEVER (주의)

1. ~에서 git init 진행
2.  리포 안에 리포 만들기
3.  git init 입력 전 확인할 점
   1. ~인지
   2. (master) 떠 있는지





초기화시점 1회 입력

$git init



작업하며 계속 입력

$git add <filename>

$git commit -m 'NESSAGE'



모니터명령어

$git status

$git log



질문

https://docs.google.com/spreadsheets/d/18qQ0EbsdiOE0Py_Gphcrlql96Ydo-G1jPQJCKU3fqZQ/edit#gid=0





