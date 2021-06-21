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

