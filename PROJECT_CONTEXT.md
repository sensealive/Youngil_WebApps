# 프로젝트 컨텍스트

## 목적

이 저장소는 **Youngil_WebApps** — 웹 기반 유틸리티·페이지를 모아 두는 공간입니다.

## 현재 구성(개요)

- 정적 HTML/CSS/JavaScript 기반 페이지
- 예: 명절 선물 추첨 등 단일 HTML 앱

## 기술 스택

- 클라이언트: HTML5, CSS3, 바닐라 JavaScript(해당 파일 기준)
- 빌드 도구: 없음(또는 추후 추가 시 이 문서 갱신)

## 디렉터리·파일 규칙

- 루트 또는 기능별로 HTML을 두고, 공통 자산은 필요 시 `assets/` 등으로 정리
- 팀/개인 컨벤션은 `.cursor/rules/project-rules.mdc`와 동기화

## 운영 메모

- 배포 URL, 호스팅 방식이 정해지면 여기에 요약해 둡니다.

### GitHub 배포/바로가기 운영 규칙

- 원격 저장소 기준: `https://github.com/sensealive/Youngil_WebApps`
- 정적 페이지 배포 후 `ShortCut` 폴더에 해당 URL 바로가기를 둡니다.
- 예시 URL: `https://sensealive.github.io/Youngil_WebApps/명절선물뽑기.html`
- .url 파일을 항상 ASCII(퍼센트 인코딩) URL만 저장.
- 바로가기 생성후 그 사이트에 접속하여 잘 작동하는지 확인 할 것.


### `git push` 작업 의미

- `sensealive` 계정 하위의 현재 프로젝트 저장소에 커밋과 푸시를 진행합니다.
- 저장소가 아직 없으면 먼저 저장소를 생성한 뒤 커밋/푸시를 진행합니다.

### `git pull` 작업 의미

- 원격 기준: `https://github.com/sensealive/<현재프로젝트명>`
- 로컬 기준 경로: `D:\programming\Cursor\Cusor_Project`
- 해당 로컬 경로로 최신 변경사항을 pull 합니다.
