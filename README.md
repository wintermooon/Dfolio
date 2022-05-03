# Dfolio

## 📆 프로젝트 기간

- 일정 : 2022-03-12(화) ~ 2022-03-27(토)  
<br>  

# ❤️‍🔥 개발자들!

팀원: BE : 박지수 김남기 선혜주, FE : 박예솔 한지선 박상언  
팀장: 박예솔 
<br>   

## `🌞 MEETING TIME`

---
 `DAILY SCRUM` 매일 오전 10시에 미팅을 진행하며, Gitlab wiki에 미팅 log작성
 `DAILY MERGE` 자신이 작성한 코드를 기능 단위 별로 merge 합니다.

 `**TEAMWORK TIME**`  **공식적인 협업 시간은 오전 10시부터 오후 6시까지**입니다. 

<br>  

## `✅ TEAM RULES`

---

1. **매일 오전 10시 스크럼 미팅에 참석하기**
  - 체크인
  - 어제 한 일 / 오늘 할 일 정리 / 힘든 점 / 배운 점 각자 정리 후 공유하기!
  - merge request 피드백 공유
2. **매일 오후 5시 30분 오후 미팅 참석하기**
  - 오늘 한일 / 질문 정리
  - 협업을 진행하며 불편사항, 어려웠던 점 정리, 유지 하고 싶은 것 정리
  - 코드 대청소 (클린 코드)
<br>  


## `🎀 CODE CONVETION`

---

- Preetier, esLint로 코드 통일화
    - .prettierrc 파일 추가(예정)
- 변수명
    - cmelCase 사용 (함수명 포함)
- 매개변수 명
    - response, request는 res, req로 통일
    - event는 e로 통일
    - error는 error로 통일
- class명은 대문자로 시작
- 함수 표현식 사용
- 주석
    - 코드 시작 부분 윗줄에 쓰기.
    - 간결하게 적고, 이해가 필요하다 싶으면 덧붙여서 설명

<br>     

## `💻 BRANCH RULES`

---

1. main(master) 브랜치에 dev 브랜치를 생성합니다.
2. dev 브랜치에 기능 MVP를 front/back으로 나눠 생성합니다.
    1. 추가적인 브랜치 생성이 필요할 경우, 오전-오후 스크럼 미팅 시간대를 활용해주세요!

<br>     

## `🔌 GIT MERGE`

---

- git merge 하기
    1. git checkout dev
    2. git merge origin/피처브랜치
    -> merge conflict 생기는 부분은 내용 수정한 후 저장 -> add, commit, push
- merge한 내용 각자 피처 브랜치로 가져오기
    1. git checkout 피처 브랜치
    2. git pull origin dev

<br>     

## `🎈 COMMIT MESSAGE`

---
- Fix A: A를 수정합니다
- Add A: A를 추가합니다
- Remove A: A를 삭제합니다.
- Refactor A: 전면 수정이 있을 때 사용합니다.
- Simplify A: A를 단순화 합니다.
- Correct A: A를 고칩니다.(주로 문법 오류나 타입의 변경, 이름변경)

<br>     
