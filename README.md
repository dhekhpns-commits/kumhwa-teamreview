# 금화피앤에스 팀 단위 평가 시스템 정적 배포본

원본 사이트: https://kumhwa-teamreview.bolt.host/

이 폴더는 GitHub Pages에 바로 올릴 수 있도록 정리한 정적 파일 묶음입니다. 별도 빌드나 설치 과정 없이 이 폴더 안의 파일을 그대로 저장소 루트에 올리면 됩니다.

## 포함 파일

- `index.html`: 메인 진입 파일
- `404.html`: GitHub Pages에서 새로고침이나 직접 주소 접근 시 앱이 열리도록 하는 fallback 파일
- `assets/index-XNLUaOs5.js`: 원본 앱 JavaScript 번들
- `assets/index-ocitREYW.css`: 원본 스타일 번들
- `assets/google-fonts.css`, `assets/fonts/`: Google Fonts를 로컬 파일로 정리한 폰트 묶음
- `assets/bolt-badge.js`: 원본 Bolt 배지 스크립트
- `금화피앤에스_로고_2048.png`: 로고 이미지
- `assets/og_default.png`: 공유 이미지
- `asset-manifest.json`: 내려받은 파일 목록과 정리 메모

## GitHub Pages 업로드

1. 새 GitHub 저장소를 만듭니다.
2. 이 폴더 안의 파일과 폴더를 저장소 루트에 모두 올립니다.
3. GitHub 저장소의 `Settings` > `Pages`에서 배포 소스를 `Deploy from a branch`로 선택합니다.
4. Branch는 `main`, folder는 `/ (root)`로 지정합니다.
5. 배포가 끝나면 표시되는 GitHub Pages 주소로 접속합니다.

## 참고

원본 앱 번들 안에는 Supabase 백엔드 주소가 그대로 포함되어 있습니다. 로그인이나 데이터 기능이 GitHub Pages 주소에서 막히면 Supabase 쪽 허용 도메인 설정에 새 GitHub Pages 주소를 추가해야 할 수 있습니다.
