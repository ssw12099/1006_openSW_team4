# branches

## Moving Through Time

Restore sisterly peace.
자매 사이의 평화를 되찾으세요

동생이 가져간 동전 10개를 다시 언니저금통으로 돌려준다.
돌려준 이후 커밋을한다.

파일 수정사항

little_sister
A young girl with brown, curly hair.
Has 10 coins. -> It is empty.

piggy_bank
This piggy bank belongs to the big sister.
It is empty. -> Has 10 coins.

사용 명령어

git add .
git commit

## Make Parallel Commits

아이와 사자가 모두 행복한 새로운 타임라인 만들기.

문제1: Make sure that the child is happy.
문제2: Make sure that the lion gets something to eat.

기존 커밋을 확인하여 문제가 발생하기 전의 커밋으로 돌아간 후 새로운 커밋을 생성한다.

확인한 커밋 상태

2번 커밋: 아이는 사탕을 가지고 있고, 사자는 배고픈 상태
3번 커밋: 아이는 사탕을 가지고 있고, 사자는 배고픈 상태
4번 커밋: 사자는 행복하지만 아이가 사라진 상태

진행 방법

git checkout HEAD^ 명령어로 이전 커밋으로 이동한다.
아이와 사자가 모두 행복할 수 있도록 파일을 수정한 뒤 새로운 커밋을 생성한다.

사용 명령어

git checkout HEAD^
git add .
git commit

## Creating Branches

문제1: Create a branch called 'birthday' that points to the birthday timeline.
문제2: Create a branch called 'concert' that points to the concert timeline.

생일 파티와 콘서트 파티에 각각 갈 수 있도록 브랜치를 생성한다.

git checkout 카드를 이용하여 각 커밋으로 이동한다.
you 파일을 확인하여 생일 파티와 콘서트 파티를 구분한다.
각 커밋에서 birthday, concert 브랜치를 생성한다.

사용 명령어

git branch birthday
git branch concert

각 명령어는 해당 커밋으로 이동한 후 실행한다.