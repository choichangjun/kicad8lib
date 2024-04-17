# kicad8lib
Kicad Libary for CCJ 


    git init
    git clone https://github.com/choichangjun/kicad8lib.git
    git remote add origin https://github.com/choichangjun/kicad8lib.git
    git fetch origin

    git checkout -b main origin/main
    git pull origin main

    git log
    git status


처음부터 시작하는 경우(권장):
git init으로 초기화한다. 
일반적으로 git clone을 사용하여 원격 저장소를 로컬로 복사하면 저장소가 자동으로 초기화됩니다.


기존 git 초기화 폴더를 사용해야 하는 경우:
이미 git init을 실행한 폴더가 있고 https://github.com/choichangjun/kicad8lib.git에서 콘텐츠를 가져오려면 다음 단계를 따르세요.

원격 저장소 추가:
git remote add origin https://github.com/choichangjun/kicad8lib.git

원격 저장소에서 모든 브랜치와 태그를 가져옵니다:
git fetch origin

원격 브랜치를 추적하는 새 로컬 브랜치(예: 원격 저장소의 기본 브랜치인 경우 main)를 확인하세요.
git checkout -b main origin/main

또는 원격 분기를 로컬 분기로 직접 가져올 수도 있습니다:
git pull origin main

방금 초기화한 이후로 저장소에 커밋이 없다면 충돌 없이 작동할 것입니다. 커밋한 경우 수동으로 해결해야 하는 충돌이 발생할 수 있습니다.

커밋 내역 확인
git log

작업 디렉터리의 현재 상태를 확인하세요
git status
