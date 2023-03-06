# haru

## Commit Convention

1. `feature`: **새로운 기능 추가**
2. `fix`: **버그 수정**
3. `docs`: **문서 수정**
4. `style`: **코드 포맷팅 → Code Convention**
5. `refactor`: **코드 리팩토링**
6. `test`: **테스트 코드**
7. `chore`: **빌드 업무 수정, 패키지 매니저 수정**
8. `comment`: **주석 추가 및 수정**

커밋할 때 헤더에 위 내용을 작성하고 전반적인 내용을 간단하게 작성합니다.

### 예시

> `git commit -m "feature: 하루"`

커밋할 때 상세 내용을 작성해야 한다면 아래와 같이 진행합니다.

### 예시

> `git commit`  
> 어떠한 에디터로 진입하게 된 후 아래와 같이 작성합니다.  
> `[header]: 전반적인 내용`  
> . **(한 줄 비워야 함)**  
> `상세 내용`

## Branch Naming Convention

브랜치를 새롭게 만들 때, 브랜치 이름은 항상 위 `Commit Convention`의 Header와 함께 작성되어야 합니다.

### 예시

> `feature/haru`  
> `refactor/haru`

---

# 필독) 초기 설정
1. `git clone --recurse-submodules https://github.com/day-23/haru.git`
2. 각 폴더에 파일이 잘 복사되었는지 확인합니다.
3. 현재 브랜치 확인 후 작업 시작합니다.

이후 업데이트 사항이 있을 경우, 업데이트를 해야할 때
1. `git submodule update --remote --recursive`  
   `--recursive` -> 하위 모듈 아래 하위 모듈을 업데이트하는 명령어로 이 repository에서는 필요없지만 해도 됩니다.
2. 업데이트 후 main 브랜치 확인하여 `git pull` 명령어를 실행합니다.
