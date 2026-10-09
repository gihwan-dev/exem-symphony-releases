# Exem Symphony 배포

Exem Symphony macOS 앱의 설치 파일을 올리는 저장소입니다. 코드는 이 저장소에 없습니다.

## 설치

1. [최신 릴리스](https://github.com/gihwan-dev/exem-symphony-releases/releases/latest)에서 `Exem-Symphony-…-arm64.zip`을 내려받습니다.
2. 압축을 풀고 `Exem Symphony.app`을 **응용 프로그램** 폴더로 옮깁니다.
3. 앱을 엽니다.

Apple Silicon Mac 전용입니다. 앱은 Developer ID로 서명돼 있고 Apple 공증을 받았습니다.

## 업데이트

직접 받을 필요가 없습니다. 앱이 이 저장소의 최신 릴리스를 30분마다 확인합니다. 새 버전이 있으면 내려받아 서명·공증·체크섬을 검증한 뒤 **업데이트 후 재시작** 버튼을 띄웁니다. 버튼을 누르면 데이터를 백업하고 앱을 교체합니다.

각 릴리스에는 앱이 검증에 쓰는 `release.json`(빌드 식별자, 커밋, SHA-256, 팀 ID)이 함께 올라갑니다.
