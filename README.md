# Today I Learned

# Git

- 버전 관리 프로그램    

- 백업, 복구, 협업에 사용

- 버전 관리 종류
  - 중앙 집중식 버전 관리
    - 중앙 서버에 문제가 생길 경우, 그 안에 있던 모든 데이터가 소실될 가능성이 높음
    - 다른 컴퓨터에 백업된 적이 없기 때문에 백업 및 복구가 어려움
  - 분산 버전 관리
    - 중앙 서버에 문제가 생겨도 각 사용자의 컴퓨터에 버전별 백업 파일이 있기 때문에 복구 및 관리가 쉬움



## Git 명령어

1. Git 초기 설정 (일회성)
   - git init


2. git 시작하기 (일회성)
   - git config --global user.name "이름"
   - git config --global user.email "깃허브 메일"


3. git 파일들의 상태 확인
   - git status


4. 변경사항 내역 확인
   - git log
     - --oneline 한 줄로 보기 옵션
     

5. 무대 위로 올리기
   - git add *파일명*
     - git add . : 현재 디렉토리에 있는 모든 파일이 올라감
     

6. 변경사항 기록하기
   - git commit -m "변경 사유"
     - -m 옵션 꼭 붙이기
     - 안 붙이면 vim으로 들어가짐
     
   
7. 원격 연결
   - git remote add origin *URL*
     - 로컬 repository와 깃허브 repository 연결
   - git push origin *메인브랜치(master)*


\* 수정된 파일이 있으면 새로 commit 하라고 git에서 알려줌.



# 마크다운

- 마크업(ex. HTML)이 경량화 된 버전

마크업 <-> 마크다운?
서로 완전 반대되는 개념은 아님