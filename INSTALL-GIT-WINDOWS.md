# Windows에서 Git 설치 가이드

이 문서는 Windows 환경에서 Git을 설치하고 기본 설정을 완료하는 방법을 단계별로 설명합니다.

---

## 1. Git 다운로드
- 공식 사이트: [https://git-scm.com](https://git-scm.com)
- "Download for Windows" 버튼 클릭 → 최신 버전 설치 파일 다운로드

---

## 2. 설치 파일 실행
- 다운로드한 `.exe` 파일 실행
- 설치 마법사(Installer) 시작

---

## 3. 설치 옵션 선택
- 기본값(Default) 그대로 두는 것을 권장
- 주요 옵션:
  - Git Bash 설치 (명령어 입력용 터미널)
  - Git GUI 설치 (그래픽 인터페이스)

---

## 4. PATH 환경 변수 설정
- "Adjusting your PATH environment" 단계에서  
  **Git from the command line and also from 3rd-party software** 선택  
- Windows 명령 프롬프트에서도 Git 사용 가능

---

## 5. 기타 설정
- HTTPS 전송 방식: 기본값 "OpenSSL" 유지
- 줄바꿈 설정: "Checkout Windows-style, commit Unix-style line endings" 선택 (권장)
- 터미널 에뮬레이터: 기본값 "Use MinTTY" 유지

---

## 6. 설치 완료
- "Finish" 버튼 클릭
- Git Bash 또는 명령 프롬프트에서 Git 사용 가능

---

## 7. 설치 확인
```bash
git --version
- 버전 정보가 출력되면 설치 성공


---


## 8. 사용자 정보 설정

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

- Commit기록에 본인 이름과 이메일이 남도록 설정

