# 💻 2023 한밭대학교 정보통신공학과 캡스톤 디자인
> _**" 커스텀 리폼 디자인 거래 플랫폼 "** 을 주제로 진행합니다._

<br>

### 1. 팀원소개
| 이름 | 학과 | 역할 |
|:-----:|:-----:|:-----:|
|이승희|정보통신공학과|Back-end|
|정현아|정보통신공학과|Front-end|
|황혜빈|정보통신공학과|Front-end|

<br>

### 2. Commit 규칙
> " Type: message " 형태로 작성한다.
- `feat` : 새로운 기능 추가에 관한 모든 사항
- `update` : 버그 없는 기능에 한한 업데이트
- `remove` : 파일 삭제
- `rename` : 파일 및 폴더 이름 변경
- `comment` : 주석 추가 및 변경
- `refactor` : 코드 리펙터링
- `docs` : 문서 수정
- `fix` : 버그 수정
- `HOTFIX` : 급하게 치명적인 버그 수정
- `chore` : 빌드 관련 파일, 패키지 매니저 수정 (`.gitignore` or `build.gradle`)
    - 프로덕션 코드 변경 x

<br>

### 3. PR 규칙
1. 제목은 50자 내로 작성한다.
2. 내용은 "어떻게" 보다 "무엇을, 왜" 위주로 작성한다.
3. 내용은 `-` 목록으로 내용을 작성한다.
4. 내용은 과거형이 아닌 
5. 커밋 타입이 다를 경우, 밑줄 후 새로운 행을 작성한다.
6. PR 템플릿은 다음과 같다.
```markdown
### 💡 COMMIT TYPE 

- 내용 작성

// example

### 💡 Feat

- 내용 작성

---

### 💡 Refactor

- 내용 
```

<br>

### 3. Local 에서 프로젝트 관리
* 원격 저장소(repository) 에 있는 ssh 주소 copy 후 local 에 저장
```shell
git clone git@github.com:???.git
```
<br>

* Local repository 에 저장된 내용을 원격 저장소에 업로드
```shell
git add 파일     // if, 현재 위치에서 업데이트 된 모든 파일을 업로드하고 싶을 경우 → . 사용
git commit -m "message"
git push        // or <git push orgin/main> or <git push main>
```
<br>

* 업데이트된 원격 저장소 local 에도 적용
```shell
git pull      
```
