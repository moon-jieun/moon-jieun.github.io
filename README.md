# Mobile Wedding Invitation

GitHub Pages에 바로 올릴 수 있는 단일 파일 모바일 청첩장입니다.

## 파일

- `index.html`: 화면, 스타일, 동작이 모두 들어있는 정적 페이지

## 구조

`index.html` 안의 표시 데이터는 간단한 XOR + Base64 포맷으로 묶어서 런타임에 주입합니다. 보안 목적의 암호화는 아니고, HTML 원문에서 이름/연락처/계좌번호가 바로 검색되는 것만 줄이는 수준입니다.

## GitHub Pages 배포

1. 이 폴더를 GitHub 저장소로 push합니다.
2. GitHub 저장소의 `Settings > Pages`로 이동합니다.
3. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
4. Branch를 `main`, 폴더를 `/root`로 설정합니다.
5. 저장 후 표시되는 Pages URL로 접속합니다.

별도 빌드 과정이나 서버가 필요 없습니다.
