# TIL (Today I Learned)

| 날짜     | 주제          | 키워드                                                                                 | 주의사항                                             |
|----------|---------------|---------------------------------------------------------------------------------------|----------------------------------------------------|
| 25.01.16 | 로컬 작업     | `git init`, `git add`, `git commit`, `git commit --amend`, `git status`, `git log --oneline` | `git commit --amend`는 커밋 히스토리가 변경되므로 주의 필요 |
|          | 원격 작업     | `git clone`, `git remote add`, `git push`, `git pull`, `git remote -v`, `git remote rm` | `git pull`은 충돌이 발생할 수 있으므로 사용 전 확인 |
|          | 기타          | `gitignore`                                                                           | `.gitignore` 파일 작성 시 경로와 파일명 주의          |

| 날짜     | 주제          | 키워드                                                                                 | 주의사항                                             |
|----------|---------------|---------------------------------------------------------------------------------------|----------------------------------------------------|
| 25.01.17 | 반복문        | `for`, `while`, `range`, `split`, `map`                                               | 반복문 내 변수명 중복 사용 주의 (`for numbers in numbers` 등) |
|          | 조건문        | `if`, `%`, `==`, `!=`                                                                 | 나눗셈(%) 연산을 활용한 홀수/짝수 판별 확인         |
|          | 리스트 처리   | `list()`, `sorted()`, `len()`, `append()`                                              | 리스트 정렬 후 원본 데이터 변화 여부 확인 필요      |
|          | 문자열 처리   | `split()`, `len()`                                                                    | 문자열로 입력받은 데이터는 항상 형 변환 필요        |
|          | 기타          | `input()`, `print()`, `random.choice()`                                               | 함수의 반환값과 출력값 구분 (`print(print(1))` 등) |

| 날짜     | 주제          | 키워드                                     | 주의사항                                             |
|----------|---------------|-------------------------------------------|----------------------------------------------------|
| 25.01.20 | 홀수의 합 구하기 | `for`, `if`, `%`, `+=`, `input()`, `map()` | 리스트 내 홀수 판별을 위해 `% 2 == 1` 조건 사용. 중첩 변수명 주의 (`for numbers in numbers`). |
|          | 리스트 평균 계산 | `sum()`, `len()`, `round()`, `input()`     | Python의 반올림 규칙 (`round()`)을 정확히 이해 필요. |
|          | A와 B 증가 합산 | `while`, `if`, `+=`, `map()`               | \( A, B \) 값이 \( N \) 이상일 경우 즉시 종료 처리 필요. |
|          | 두 수 비교     | `if-elif-else`, `>`, `<`, `=`              | \( A, B \) 값이 동등할 경우를 정확히 처리해야 함. |
|          | 369 게임 변형  | `str.replace()`, `for`, `if`, `input()`    | 숫자를 문자열로 변환 후 `3`, `6`, `9`를 `-`로 대체. 숫자가 제거된 경우 결과값이 정확히 출력되도록 주의. |
| 날짜     | 주제                      | 키워드                                          | 주의사항                                                                                       |
|----------|---------------------------|------------------------------------------------|----------------------------------------------------------------------------------------------|
| 25.01.21 | `is`와 `==` 차이점        | `is`, `==`, 메모리 주소                        | - `is`는 객체 식별성(메모리 주소)을 비교, 값 비교는 적합하지 않음.<br>- 숫자, 문자열 비교는 `==` 사용. |
|          | Trailing Comma           | 쉼표, 리스트, 권장사항                         | 리스트와 딕셔너리 등에서 후행 쉼표를 사용하는 것이 유지보수에 유리함. 한 줄에 작성은 권장하지 않음.       |
|          | 얕은 복사와 깊은 복사     | 얕은 복사 (`[:]`), `copy.deepcopy`             | 얕은 복사와 깊은 복사의 차이를 이해해야 데이터 불변성을 유지 가능.<br>특히 중첩 리스트에서는 `deepcopy` 권장. |
|          | 데이터 추출 및 변환       | 딕셔너리,                   | JSON 형태에서 딕셔너리 값 접근 방법 연습.<br>중첩 구조 접근 시 키 경로를 정확히 파악해야 함.              |

| 날짜     | 주제                      | 키워드                                      | 주의사항                                                                                   |
|----------|---------------------------|--------------------------------------------|------------------------------------------------------------------------------------------|
| 25.01.22 | 함수의 반환값과 변수 스코프 | `return`, `global`, `local`, `None`         | - 함수에서 반환값이 없으면 `None`이 기본 반환값.<br>- `global` 키워드 없이 전역 변수를 수정할 수 없음. |
|          | 재귀 함수                 | `factorial`, `재귀`, `base case`            | - 재귀 함수는 반드시 종료 조건 (`base case`)이 필요.<br>- 재귀 깊이 제한 확인 필요 (`RecursionError`). |
|          | 제어문 내 `return`         | `for`, `if`, `return`, `break`             | - `return`은 함수 실행을 즉시 종료.<br>- 함수 외부에서는 사용할

---
