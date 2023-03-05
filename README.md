# haru

필독) 초기 설정
1. `git clone --recurse-submodules https://github.com/day-23/haru.git`
2. 각 폴더에 파일이 잘 복사되었는지 확인합니다.
3. 현재 브랜치 확인 후 작업 시작합니다.

이후 업데이트 사항이 있을 경우, 업데이트를 해야할 때
1. `git submodule update --remote --recursive`  
   `--recursive` -> 하위 모듈 아래 하위 모듈을 업데이트하는 명령어로 이 repository에서는 필요없지만 해도 됩니다.
2. 업데이트 후 main 브랜치 확인하여 `git pull` 명령어를 실행합니다.
