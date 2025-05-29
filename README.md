# 👋 hello-git

Git과 GitHub 기본기를 익히기 위한 실습용 레포지토리입니다.  
버전 관리, 커밋, 브랜치, 병합, 충돌 해결, PR 등 실전 Git 사용법을 단계별로 연습합니다.

---

## 📌 학습 목표

- Git의 기본 명령어 사용법 이해
- 로컬/원격 저장소 연결 및 푸시
- 브랜치 생성 및 병합
- 커밋 히스토리 관리
- 충돌 해결 실습
- GitHub에서의 Pull Request 경험

---

## 📂 실습 내용

| 폴더/파일 | 설명 |
|-----------|------|
| `step1/`  | Git 초기 설정 및 첫 커밋 |
| `step2/`  | 브랜치 생성과 병합 연습 |
| `step3/`  | 충돌 상황 만들기 & 해결 연습 |
| `README.md` | 리포지토리 소개 문서 |

---

## 🛠 사용 명령어 예시

```bash
# Git 초기화
git init

# 커밋하기
git add .
git commit -m "커밋 메시지"

# 브랜치 만들기
git checkout -b feature-branch

# 병합하기
git checkout main
git merge feature-branch
