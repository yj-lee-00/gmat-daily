# GMAT Daily Set (GitHub Pages 버전)

폰 홈 화면에 앱처럼 설치해서 쓰는 GMAT 데일리 연습 앱입니다.

## 파일
- `index.html` — 앱 본체
- `questions.json` — 문제 은행 (새 문제는 이 파일에 추가됨)
- `pretendard-subset.woff2` — Pretendard 폰트(자주 쓰는 한글 2,350자 + 영문, OFL 라이선스)
- `manifest.webmanifest`, `sw.js`, 아이콘 — 홈 화면 설치·오프라인용

## 올리는 법
1. GitHub에서 새 저장소 `gmat-daily` 만들기 (Public)
2. **Add file → Upload files**로 이 폴더 안의 파일을 전부 올리고 Commit
3. **Settings → Pages → Build and deployment**에서 Source를 `Deploy from a branch`, Branch를 `main` / `/ (root)`로 저장
4. 1~2분 뒤 `https://<아이디>.github.io/gmat-daily/` 에서 열림

## 홈 화면에 추가
- 아이폰: Safari로 열기 → 공유 버튼 → **홈 화면에 추가**
- 안드로이드: Chrome으로 열기 → 메뉴(⋮) → **앱 설치** 또는 **홈 화면에 추가**

## 알아둘 점
- 이 버전의 풀이 기록은 **그 기기 안에만** 저장됩니다(localStorage). 다른 기기와는 동기화되지 않아요.
- 새 문제는 `questions.json`이 갱신되면 앱을 다시 열 때 자동으로 반영됩니다.
