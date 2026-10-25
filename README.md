# Market Peek

바탕화면에서 코인·한국·미국 주식 시세와 거래소 포지션을 확인하는 데스크톱 앱입니다. Windows에서는 작업 표시줄 시세도 지원합니다.

[프로그램 소개와 설치 안내](https://duki-programming.github.io/market-peek/) · [English](https://duki-programming.github.io/market-peek/en/) · [최신 릴리스](https://github.com/Duki-Programming/Market-Peek-releases/releases/latest) · [버전별 다운로드](https://github.com/Duki-Programming/Market-Peek-releases/releases)

## 다운로드

| 운영체제 | 버전 | 다운로드 |
| --- | --- | --- |
| Windows 64비트 | v1.0.4 Beta | [설치 EXE](https://github.com/Duki-Programming/Market-Peek-releases/releases/download/v1.0.4/Market.Peek.Setup.1.0.4.exe) · [7z](https://github.com/Duki-Programming/Market-Peek-releases/releases/download/v1.0.4/market-peek-1.0.4-x64.7z) |
| macOS Universal | v1.0.4 Beta | [설치 DMG](https://github.com/Duki-Programming/Market-Peek-releases/releases/download/v1.0.4/market-peek-1.0.4-universal.dmg) |

공개된 설치 파일을 표시합니다. macOS 파일이 최신 릴리스보다 오래된 버전이면 새 파일을 준비하는 동안 다운로드를 제공하지 않습니다.

- **EXE**: 한국어 설치 안내에 따라 설치합니다.
- **7z**: 압축을 모두 푼 뒤 폴더 안의 `Market Peek.exe`를 실행합니다.
- **DMG**: Mac에서 열어 앱을 Applications로 복사합니다. Apple Silicon과 Intel을 지원합니다.
- **SHA256SUMS.txt / SHA256SUMS-mac.txt**: 각 릴리스의 배포 파일 해시입니다.

Python을 따로 설치할 필요가 없습니다. Windows 설치 파일에는 Authenticode 서명이 없어 게시자 확인 안내가 표시될 수 있습니다.

## 앱 업데이트

업데이트를 지원하는 설치본은 시작할 때 새 버전을 확인합니다. 자동 설치 기능이 포함된 새 설치본은 **업데이트**를 한 번 누르면 다운로드·검증·설치·재실행까지 진행합니다. Windows는 Setup에 포함된 NSIS 기능을, Mac은 앱 내부의 도우미를 사용합니다. 설정과 API 정보는 유지하며 설정의 **업데이트 확인**으로 수동 확인도 가능합니다.

업데이트 서명과 설치 파일의 해시를 검증합니다. Mac 도우미는 DMG 하나에 포함되며 Apple Developer ID 없이 앱을 교체합니다. 새 앱의 시작을 확인하지 못하면 이전 앱으로 복구하고, 설치 위치에 쓰기 권한이 없으면 DMG로 직접 교체하도록 안내합니다. 도우미가 없는 기존 Mac 1.0.2·1.0.3은 새 설치본으로 한 번 업데이트해야 합니다.

초기 Windows 1.0.2 설치본에는 GitHub 파일명 처리로 앱 내 업데이트 다운로드가 실패하는 문제가 있습니다. 교체된 1.0.2 설치 파일은 릴리스 페이지에서 한 번 직접 재설치해 주세요. 같은 버전 교체는 앱에서 업데이트로 인식하지 않습니다.

## 버전 기록

| 버전 | 변경 내용 |
| --- | --- |
| [v1.0.4 Beta](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.4) | [변경 내용 보기](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.4) |
| [v1.0.3 Beta](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.3) | [변경 내용 보기](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.3) |
| [v1.0.2 Beta](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.2) | [변경 내용 보기](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.2) |
| [v1.0.1 Beta](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.1) | [변경 내용 보기](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.1) |
| [v1.0.0 Beta](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.0) | [변경 내용 보기](https://github.com/Duki-Programming/Market-Peek-releases/releases/tag/v1.0.0) |

이 저장소는 배포 파일과 버전 기록을 제공합니다. 프로그램 소스 코드는 포함하지 않습니다.

개발·제작: **Duki Programming**

<!-- 배포 명령이 공개된 릴리스를 기준으로 자동 생성합니다. 원본: distribution/README.template.md -->
