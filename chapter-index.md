# index

## Step by step

Pick the timeline that's clearer, and make the alarm go off!
변경 과정이 더 명확한 타임라인을 선택하고 화재경보기가 울리도록 만든다.

all-at-once: 모든 변경 사항을 한 번에 커밋한 브랜치
step-by-step: 변경 사항을 단계별로 나누어 커밋한 브랜치

step-by-step 브랜치로 이동하여 smoke_detector 파일을 수정한 뒤 커밋한다.

사용 명령어

git checkout step-by-step
git add .
git commit -m "Alarm goes off"

파일 수정내용

smoke_detector
The alarm goes off. #화재경보기가 울리도록 수정

## Add new files to the index

문제1: Add the candle.
문제2: Make a commit.

candle 파일을 index에 추가한 후 커밋한다.

index는 다음 커밋에 포함할 파일을 미리 준비하는 공간이다.

사용 명령어

git add candle
git commit -m "Add candle"