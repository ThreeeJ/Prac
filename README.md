# Prac

> 이 프로젝트는 [한 줄로 멋지게 프로젝트를 설명해주세요]를 위한 연습용 프로젝트입니다.

---

## 📌 프로젝트 소개

> 여기에 프로젝트를 시작하게 된 계기, 목표, 주요 개발 기간, 기획 의도 등을 자유롭게 작성해주세요.
>
> 예시)
>
> - **프로젝트 목표:** Spring Boot와 JPA, 그리고 OpenAI API를 활용하여 [어떤 기능]을 제공하는 웹 애플리케이션을 개발하는 것입니다.
> - **개발 기간:** 20xx.xx.xx ~ 20yy.yy.yy

---

## ✨ 주요 기능

> 이 프로젝트의 핵심 기능들을 목록으로 정리해주세요.
>
> 예시)
> - **[기능 1]:** 로그인 및 회원가입 기능
> - **[기능 2]:** AWS S3를 이용한 이미지 업로드 및 관리
> - **[기능 3]:** OpenAI GPT API를 연동한 AI 챗봇 기능
> - **[기능 4]:** ...

---

## 🛠 기술 스택

- **Language**: Java 21  
- **Framework**: Spring Boot 3.x  
- **Build Tool**: Gradle  
- **Database**: MySQL  
- **ORM**: Spring Data JPA  
- **Cloud**: AWS S3 (이미지 업로드)  
- **AI API**: OpenAI GPT API

---

## 🚀 시작하기

### 📦 설치 및 실행 방법

1. **레포지토리 클론:**

    ```bash
    git clone https://github.com/[your-username]/Prac.git
    ```

2. **프로젝트 디렉토리로 이동:**

    ```bash
    cd Prac
    ```

3. **의존성 설치 및 빌드:**

    ```bash
    ./gradlew clean build
    ```

4. **애플리케이션 실행:**

    ```bash
    ./gradlew bootRun
    ```

5. **(선택) 테스트 실행:**

    ```bash
    ./gradlew test
    ```

---

## ✍️ 개발 규칙

### 🚩 Git 명령어

| 명령어 | 설명 |
| :--- | :--- |
| `git clone <url>` | 원격 저장소 복제 |
| `git add .` | 전체 변경 파일 스테이징 |
| `git add <파일명>` | 특정 파일만 스테이징 |
| `git commit -m "메시지"` ⭐ | 커밋 메시지와 함께 커밋 |
| `git log` | 커밋 히스토리 확인 |
| `git fetch` | 원격 저장소의 브랜치 상태를 가져오기 |
| `git branch` | 현재 브랜치 목록 확인 |
| `git checkout <이름>` ⭐ | 해당 브랜치로 이동 |
| `git checkout -b <이름>` | 새 브랜치 생성 + 이동 |
| `git push` ⭐ | 현재 브랜치 내용을 원격 저장소에 푸시 |
| `git pull origin main` ⭐ | 원격 `main` 브랜치 내용 가져오기 (병합) |
| `git push --set-upstream origin <이름>` | 로컬 브랜치와 원격 브랜치를 연결 |

### ✏️ 커밋 메시지 규칙

모든 커밋은 아래 규칙을 따릅니다.  
Gitmoji와 Conventional Commit 스타일을 함께 사용합니다.

#### ✅ 형식

> type: [Gitmoji] subject

-   **type:** 아래 `커밋 타입 목록`에 정의된 타입을 소문자로 작성합니다.
-   **Gitmoji:** 타입에 맞는 Gitmoji 코드를 작성합니다.
-   **subject:** 50자 이내의 짧고 간결한 요약 설명을 작성합니다.

#### 커밋 타입 목록

| 타입 | Gitmoji 코드 | 설명 |
| :--- | :--- | :--- |
| `init` | `:tada:` | 프로젝트 초기 설정 |
| `feat` | `:sparkles:` | 새로운 기능 추가 |
| `fix` | `:bug:` | 버그 수정 |
| `docs` | `:memo:` | 문서 수정 (README 등) |
| `style` | `:art:` `:lipstick:` | 코드 스타일, UI 등 서식 변경 (기능 변화 없음) |
| `refactor` | `:recycle:` | 코드 리팩토링 |
| `test` | `:white_check_mark:` | 테스트 코드 추가/수정 |
| `perf` | `:zap:` | 성능을 개선하는 코드 변경 |
| `build` | `:wrench:` `:hammer:` | 빌드 시스템 또는 외부 종속성 변경 |
| `ci` | `:green_heart:` | CI/CD 구성 파일 및 스크립트 변경 |
| `chore` | `:heavy_plus_sign:` `:package:` | 빌드, CI 등을 제외한 기타 잡다한 작업 |
| `revert` | `:rewind:` | 이전 커밋을 되돌리는 작업 |
| `remove` | `:fire:` | 코드 또는 파일 삭제 |

#### 예시

-   `init: :tada: Create project using Spring Boot`
-   `feat: :sparkles: Add user login functionality`
-   `fix: :bug: Correct image upload error on S3`
-   `docs: :memo: Update README with installation guide`

---

## 👥 팀원 소개

> 함께 프로젝트를 진행한 팀원이 있다면 소개해 보세요.
>
> | 이름 | 역할 | GitHub |
> | :--- | :--- | :--- |
> | **정종진** | **Backend Developer** | [**@ThreeeJ**](https://github.com/ThreeeJ) |
