# task

## 과제방에 repo 주소로 업로드

1. task repository 포크로 본인 repository에 복사
2. 내려 받기해서 해당 README.md 문서 수정
3. 오늘까지 배운 git 내용 마크다운 형식으로 __잘__ 정리
  _markdown-cheetseat 참고_
4. 본인 repository에 업로드
5. 로컬 저장소 내용도 캡쳐해서 함께 업로드

이 아래로 내용 작성
-

# 오늘까지 배운 내용 #

## git 이란? ##

- 파일의 변경사함을 추척하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템

## github 란? ##

- 온라인 상에서 협업을 통해 버전 관리를 할 수 있게 해주는 대표적인 깃 호스팅 업체
- Bitbucket, GitLab 등의 업체도 있음


​#_수정1_## 

- 23/03/13

## _pwd_ 

- 현재 디렉토리 위치

### cd 폴더명 ###

- 그 폴더로 들어감

### cd /e ###

- e 드라이브로 바로 이동

### cd .. ###

- 현재 디렉토리에서 바로 상위 디렉토리로 이동

### cd -  ###

- 바로 이전 디렉토리로 이동

### touch 파일명 ###

- 파일 생성

### clear ###

- 현재 콘솔창으로 보여진 입력한 것들과 출력된 것들을 화면에서 지움

### branch ###

- 기준 작업 라인

### main ###

- 기본, main branch

### commit ###

- 타임캡슐에다 넣고 커밋을 넣으면 소스 코드가 쌓임. 언제든 과거로 돌아갈 수 있음

### merge ###

- 다른 브랜치에서 작업하던 것을 합침. 그냥 합쳐지지는 않음. 
  마스터에 포함이 되려면 pullRequest(보고서 혹은 요청서로 이해)를 통해 요청

### switch 브랜치명 ###

- 해당 브랜치로 이동

### push origin main ###

- 마스터에서 있던 모든 파일들이 깃허브에 동기화(업로드)

### 파일 추가 ###

- git add .

### 메시지 작성과 함께 커밋 ###

- git commit -m

### 이력 확인 ###

- git log
- git log --oneline

### 현재 상태 확인 ###

- git status

### 브랜치 생성 ###

- git branch dev

### 브랜치 이동 ###

- git switch dev

### 브랜치 리스트 확인 ###

- git branch --list

### main 브런치에 푸시하는 경우 ###

- git push -u origin main

### github에서 파일 내려받기 ###

- main 브런치 : git pull (origin main)

### github에서 내 저장소로 복사하기(내 저장소에 폴더가 없는 경우) ###

- git clone https://~

### github에서 내 저장소로 복사하기(내 저장소에 폴더를 미리 만든 경우) ###

- git clone https://~ .  
- 주소 끝에 한 칸 띄어쓰기 후 마침표(.)