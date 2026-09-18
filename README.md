# 부부젤라 (Vuvuzela)

부부를 위한 D-Day · 할 일 · 기념일 · 가계부 · 오늘의 기분 통합 PWA.

## 배포 URL
https://hjmoon29.github.io/vuvuzela/

## 로컬 실행
```bash
node server.js
```
표시되는 `http://<LAN-IP>:8080` 주소로 접속. 같은 WiFi의 폰에서도 접속 가능.

## 배포
GitHub Pages에서 자동 호스팅. `main` 브랜치의 루트를 서빙 (push하면 몇 분 후 반영).

## 폰에 설치 (PWA)
1. 폰 브라우저(Chrome/Safari)에서 https://hjmoon29.github.io/vuvuzela/ 접속
2. **홈 화면에 추가** 선택
3. 홈 화면에서 앱처럼 실행

## 파일 구성
- `index.html` — 앱 전체 (스타일 + 마크업 + 로직)
- `manifest.json` — PWA 매니페스트
- `sw.js` — 서비스 워커 (캐시 관리, 업데이트 감지)
- `icon-192.svg`, `icon-512.svg` — 앱 아이콘
- `server.js` — 로컬 개발 서버
