# FUKUOKA TRIP 2027 — GitHub Pages

정적 웹앱입니다. 별도 서버나 빌드 과정 없이 GitHub Pages에서 공개할 수 있습니다.

## 배포 방법

1. GitHub에 로그인하고 **New repository**를 선택합니다.
2. 저장소 이름을 `fukuoka-trip` 등으로 정하고 **Public**으로 생성합니다.
3. 이 폴더의 `index.html`을 저장소 최상위(root)에 업로드합니다.
4. 저장소의 **Settings → Pages**로 이동합니다.
5. **Build and deployment → Deploy from a branch**를 선택합니다.
6. Branch는 `main`, 폴더는 `/ (root)`를 선택하고 **Save**를 누릅니다.
7. 배포가 완료되면 `https://깃허브아이디.github.io/fukuoka-trip/` 형식의 주소가 생성됩니다.

## 데이터 저장 범위

- 체크리스트, 예산, 추가 메모는 방문자의 브라우저 `localStorage`에 저장됩니다.
- 저장된 내용은 각 기기에만 남으며 다른 방문자에게 공유·동기화되지 않습니다.
- 공개 링크를 가진 사람은 페이지의 안내 내용을 볼 수 있습니다. 민감한 개인정보나 여권·예약번호를 입력하지 마세요.

## 수정 방법

GitHub 저장소에서 `index.html`을 수정하거나 교체하면 Pages가 자동으로 다시 배포합니다.

## 유의

면세 제도 및 돈키호테 쿠폰 부분은 여행 준비 메모를 바탕으로 정리했으며, 시행 여부·조건을 확정하는 공식 검증 자료가 아닙니다. 출국 전 일본 세관, 관광청, 후쿠오카 공항 및 돈키호테의 최신 공지를 확인하세요.
