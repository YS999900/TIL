# TIL
Today I Learned
git과 github의 차이
리포지토리의 종류(로컬,원격)
git의 3가지 영역
1) working Directory : 실제 작업을 편집하는 곳
2) staging Area : 다음 커밋에 담을 변경을 골라 두는 영역
3) repository : 커밋 이력이 저장되는 영역
git reset과 git revert의 차이
branch : 특정 커밋을 가리키는 움직이는 포인터. 본작업과 분리된 독립적인 작업 줄기를 만든다
필수 Git 명령어
시작.설
git config
사용자 이름·이메일 설정
git init
새 저장소 만들기
git clone
원격 저장소 복제
git remote add
원격 저장소 연결

기록
git status
현재 상태 확인
git add
Staging에 올리기
git commit
커밋 만들기
git log
이력 보기

동기화
git push
원격으로 올리기
git pull
받아서 병합 (fetch+merge)
git fetch
받기만 하고 병합 안 함

브랜치
git branch
브랜치 목록·생성·삭제
git switch
브랜치 이동 (Git 2.23+)
git checkout
이동·복원 (기존 방식)
git merge
브랜치 병합

되돌리기 · 정리
git restore
파일 변경 취소 (Git 2.23+)
git reset
HEAD 이동
git revert
되돌리는 커밋 추가
git clean
추적 안 하는 파일 삭제

대용량 파일
git lfs install
Git LFS 사용 설정
git lfs track
LFS로 관리할 확장자 지정
