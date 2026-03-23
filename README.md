<img width="1195" height="787" alt="image" src="https://github.com/user-attachments/assets/e9f18221-4562-4031-af2d-c90ec380f825" />작업 하기전 준비

1.git다운로드

https://git-scm.com/install/windows

<img width="588" height="453" alt="img1" src="https://github.com/user-attachments/assets/4fafe79a-2d36-4373-9aed-6b99ce0f7f6e" />



위 그림처럼 Add a Git Bash Profile to Window Terminal을 체크한후 설치를 합니다



<img width="210" height="68" alt="image" src="https://github.com/user-attachments/assets/82617277-633a-4911-8101-7e4d4eec3c92" />



git을 실행한 후 git --version명령어를 통하여 git이 잘 설치되었는지 확인



<img width="285" height="45" alt="image" src="https://github.com/user-attachments/assets/b7fc0751-4529-4a00-aa70-af23d4a2520b" />



윈도우와 맥에서의 엔터방식 차이를 해결하기 위해 아래 명령어를 실행



git config --global core.autocrlf true

<img width="1195" height="787" alt="image" src="https://github.com/user-attachments/assets/8f7d0296-6da7-433c-b8f5-3cab227d915c" />

VScode에서 open folder로 AI sheriff로 들어가기




<img width="1191" height="790" alt="img2" src="https://github.com/user-attachments/assets/7bedb302-311d-4e46-88d8-9ae7d6db7f5d" />




VScode를 실행한후 Select gitBash를 Default Profile로 설정



<img width="580" height="365" alt="image" src="https://github.com/user-attachments/assets/4a169673-673d-49c2-b184-50032c85074e" />



git bash에 들어가 사용자명과 사용자 이메일을 설정

git config --global user.name 이름

git config --global user.email 이메일

<img width="1234" height="215" alt="image" src="https://github.com/user-attachments/assets/7c07ee9d-a903-4ac2-9793-952b5dfcc9c6" />



github와 연결을 위해 아래 명령어를 실

git clone https://github.com/hyukjin0117/AI-Shierff.git



폴더로 돌아가 숨긴 항목표시를 활성화 하여 .git이 생성된 걸 확인



git config --global init.defaultBranch main



위 명령어를 통해 기본브랜치를 변경



git switch -c feature/이름_작업내용



위 명렬어로 브랜치를 생성 및 이동



git branch



브랜치 목록확인
