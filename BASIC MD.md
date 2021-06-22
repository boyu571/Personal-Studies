# Git basic

git의 기초를 배워요



## 저장소 초기화 하기

git init



## 저장소를 일반 디렉토리로 되돌리기

re -rf .git

## STAGE에 올리기 (staging)

특정 파일만 스테이지에 올리기

`git add  <filename>`

현재위치의 모든 파일을 스테이지에 올리기

`git add .`



## commit을 통해 스냅샷 저장하기

`git commit -m "MESSAGE"`



vim 편집기

1. 'i' 눌러서 편집모드

2. 편집

3. 'esc' 눌러서 명령모드

4. ':w' 입력 후 enter => 저장

5. ':q' Enter => 종료

6. ':wq' Enter => 저장, 종료

7. ':q!' Enter =>  저장 안하고 강제 종료

   

## 현재 상태 확인하기

`$ git status`

- 빨간색으로 표시되는 파일은 commit에 포함되지 않음

- 초록색으로 표시되는 파일은 commit에 포함됨.

- 변경사항이 없는 파일은 표시되지 않음.



## 커밋 로크 확인하기

`git log`



## CLI 다루는법

cd(클릭) = change directoy(folder 들어가기)

cd .. = 위로 가기

~ = home

touch = 파일 만드는 명령어
mkdir = 폴더 만드는 명령어

start = 파일 들어가기(실행)

rm(remove) = 파일 삭제하기
rm -r = 폴더 삭제하기
tab = 자동완성
rm *.txt = 텍스트 파일 삭제

CLI = Command LIne Interface
GUI = Graphic User Interface
rm -r *  = 전체 지우기


cp(copy) = 복사
cp a.txt copy.txt(a.txt를 복사해서 copy.txt로 만듬)

mv(move) = 이동, 이름바꾸기
mv copy.txt hi.txt(이름 바꾸기)



개발용 메일을 하나 준비(Gmail 권장) =>
개발용 메일 주소로 git config --global user.email "개발용 메일주소"
이메일로 내일 github 가입 예정
1. github 가입시 username에 대문자/띄어쓰기 섞지 않기
2. github의 username이 여러분 개발자 닉네임
