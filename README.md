<div align="center">

# 삼플 · sampple-korea

**AI 개발 도구와 Android 앱을 만들고,<br>오픈소스를 한국어 사용자에게 연결합니다.**

Building practical AI tools, Android apps, and Korean open-source localization.

<p>
  <a href="https://github.com/sampple-korea/sampple-korea/actions/workflows/update-translation-stats.yml"><img alt="Translation stats" src="https://github.com/sampple-korea/sampple-korea/actions/workflows/update-translation-stats.yml/badge.svg?branch=main"></a>
  <img alt="Translated Android XML" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fsampple-korea%2Fsampple-korea%2Fmain%2Fmetrics%2Ftranslation-xml-words-badge.json">
</p>

</div>

## 대표 프로젝트

| Project | What it does |
| --- | --- |
| [**beat-codex**](https://github.com/sampple-korea/beat-codex) | Codex의 TUI, 로컬 도구, 세션과 승인 흐름을 유지하면서 BeAT 모델을 사용하는 독립형 CLI |
| [**AuroraPure**](https://github.com/sampple-korea/AuroraPure) | Google Play가 기기에 실제 전달하는 APK 구성을 탐색하고 저장하는 Android 앱·데스크톱 CLI |
| [**MES**](https://github.com/sampple-korea/MES) | 모바일 웹에서 요소를 선택하고 동적 숨김 규칙을 관리하는 고급 userscript |
| [**Miru Live**](https://github.com/sampple-korea/mirulive) | Live2D, 실시간 AI 음성, 로컬 기억과 음성 변환을 결합한 데스크톱 동반자 |

## AI · 개발 도구

- [**beat-cli**](https://github.com/sampple-korea/beat-cli) — BeAT 터미널 클라이언트, Codex 연결과 로컬 OpenAI 호환 게이트웨이
- [**codex-web-workstation**](https://github.com/sampple-korea/codex-web-workstation) — 공식 Codex app-server를 `container2wasm`으로 브라우저에서 실행하는 무서버 타당성 검증
- [**chalna-android**](https://github.com/sampple-korea/chalna-android) — Android 어시스턴트 호출로 로컬 영상 캡처를 제어하는 앱

## 오픈소스 한국어 현지화

Android와 모바일 오픈소스 프로젝트의 한국어 현지화에 기여합니다. 단순 문자열 치환보다 실제 UI 문맥, 용어 일관성, Android 리소스 구조와 사용성을 함께 확인하는 작업을 지향합니다.

아래 수치는 공개 저장소에 병합된 PR에서 변경된 한국어 Android XML 리소스를 GitHub Actions로 매일 다시 계산한 결과입니다.

<!-- translation-stats:start -->
**39,841 translated XML words · 9,873 Android resources · 7 measured PRs**

| Project | XML words | Resources | PR |
| --- | ---: | ---: | --- |
| Operit | 28,359 | 6,887 | [#570](https://github.com/AAswordman/Operit/pull/570) |
| NagramXF | 4,193 | 1,150 | [#88](https://github.com/Keeperorowner/NagramXF/pull/88) |
| Vectras-VM-Android | 3,377 | 718 | [#661](https://github.com/xoureldeen/Vectras-VM-Android/pull/661) |
| NagramX | 2,443 | 713 | [#378](https://github.com/risin42/NagramX/pull/378) |
| local-dream | 1,040 | 297 | [#219](https://github.com/xororz/local-dream/pull/219) |
| AntiSplit-M | 239 | 59 | [#662](https://github.com/AbdurazaaqMohammed/AntiSplit-M/pull/662) |
| GameNative | 190 | 49 | [#1559](https://github.com/utkarshdalal/GameNative/pull/1559) |
<!-- translation-stats:end -->

## 주로 다루는 것

- AI CLI, 로컬 에이전트와 모델 게이트웨이
- Android, Kotlin과 Jetpack Compose
- TypeScript, JavaScript와 데스크톱 애플리케이션
- 모바일 웹 자동화와 userscript
- 한국어 현지화와 Android 리소스 검토
- GitHub Actions 기반 빌드·릴리스 자동화

<sub>삼플은 Samsung + Apple에서 만든 이름입니다.</sub>
