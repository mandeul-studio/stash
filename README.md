<div align="center">
  <img src="appicon.png" alt="App Icon"/>
</div>

# Stash - Developer's Snippet Manager

**Stash**는 개발자를 위해 설계된 가볍고 빠른 데스크탑 스니펫 관리 도구입니다. 자주 사용하는 코드 조각, 명령어(Command), 민감한 정보(Secrets)를 로컬에 안전하게 저장하고 즉시 검색하세요.

<!-- 
[스크린샷 영역 1: 메인 화면]
여기에 앱 실행 시 보이는 전체 화면 스크린샷을 넣어주세요.
예: ![Main App Screenshot](./screenshots/main-app.png) 
-->

## ✨ Key Features

*   **⚡ 초고속 검색**: 퍼지 매칭(Fuzzy Matching)을 지원하며 검색어 입력 시 즉각적인 결과를 제공합니다. (Debounce 최적화)
*   **🔒 시크릿 스태시 (Secret Stash)**: API Key, 비밀번호 등을 **AES-256 암호화**로 안전하게 보관합니다. UI에서는 마스킹 처리되며 클릭 한 번으로 안전하게 복사할 수 있습니다.
*   **⚡ 글로벌 퀵 메뉴 (Hotkeys)**: 작업 중 어느 창에서든 `Ctrl+Shift+Space` 단축키로 Stash를 즉시 호출하거나 숨길 수 있어 문맥 전환(Context Switch)을 최소화합니다.
*   **🛠 개발자 유틸리티 (Developer Utils)**: 
    *   **텍스트 & JSON**: 줄바꿈 문자열 조인(`,`), SQL 포맷팅, JSON Pretty/Minify 지원.
    *   **Timestamp**: 실시간 Unix Epoch 타임스탬프 확인 및 Date 양방향 변환.
    *   **Generator**: UUID v4 및 보안 랜덤 문자열/비밀번호 생성기.
*   **🔍 Diff Checker**: 두 텍스트나 코드 조각을 좌우(Split View)로 비교합니다. 단어 단위의 차이점 강조와 다크/라이트 테마를 완벽하게 지원합니다.
*   **📝 Markdown Previewer**: 실시간 마크다운 에디터 및 미리보기 기능을 제공합니다. GitHub 스타일의 테마와 코드 블록 문법 강조를 지원합니다.
*   **📡 HTTP Client**: API 테스트를 위한 경량 HTTP 클라이언트입니다. GET, POST 등 주요 메서드를 지원하며, 백엔드에서 요청을 처리하여 CORS 제한 없이 API를 테스트할 수 있습니다.
*   **🎨 Code to Image**: 코드를 아름다운 이미지 스냅샷으로 변환합니다. 다양한 그라데이션 배경과 테마를 선택할 수 있으며, PNG 파일로 즉시 내보낼 수 있습니다.
*   **💻 Command & Code 모드**: 
    *   `CMD`: 자주 쓰는 복잡한 터미널 명령어를 `$ ` 접두사와 함께 깔끔하게 저장.
    *   `CODE`: 다양한 언어(Go, TS, Python, SQL 등)의 문법 강조(Syntax Highlighting) 지원.
*   **💾 데이터 관리**: 
    *   **Import/Export**: 전체 데이터를 JSON 파일로 백업하거나 다른 환경으로 이전 가능.
    *   **Reset**: 필요 시 한 번의 클릭으로 모든 로컬 데이터를 초기화(Confirmation 지원).
*   **🎨 테마 지원**: 개발 환경에 맞춘 다크(Dark) 및 라이트(Light) 모드를 완벽하게 지원합니다.

<!-- 
[스크린샷 영역 2: 스니펫 추가 화면 또는 검색 화면]
스니펫을 입력하는 폼이나 검색 결과가 나온 화면을 넣어주세요.
예: ![Search and Form](./screenshots/features.png) 
-->

### 🐞 Bug Report
버그를 발견하셨다면 [Issues](https://github.com/hooneun/stash-snippet-manager/issues) 탭에서 제보해 주세요. 가능하면 재현 경로와 스크린샷을 첨부해 주시면 큰 도움이 됩니다.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
