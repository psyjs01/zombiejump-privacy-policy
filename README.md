# ZombieJump 개인정보처리방침 / 개발자 웹사이트

`public/`의 정적 파일(`ZombieJumpGodot/store/privacy_policy.html` 사본)을 GitHub Pages로 게시한다.
RockStar의 `rockstar-privacy-policy` 저장소와 같은 방식.

## 공개 주소

- 개인정보처리방침 (AdMob 메시지·Play Console 앱 콘텐츠에 등록):
  https://psyjs01.github.io/zombiejump-privacy-policy/privacy.html
- 개발자 웹사이트 (Play 스토어 등록정보):
  https://psyjs01.github.io/zombiejump-privacy-policy/

## GitHub Pages 배포

`main` 브랜치에 푸시하면 `.github/workflows/deploy-pages.yml`이 게시한다.
저장소 생성 시 Pages Source가 `GitHub Actions`로 설정돼 있어야 한다
(API `build_type=workflow` 또는 Settings > Pages에서 한 번만 설정).

## app-ads.txt

**루트 게시 완료 (2026-08-23 확인)**: 사용자 사이트 저장소(`psyjs01.github.io`) 루트의
https://psyjs01.github.io/app-ads.txt 가 이미 게시돼 있고, 내용은
`google.com, pub-8943982547557856, DIRECT, f08c47fec0942fa0` 한 줄이다.
app-ads.txt는 게시자 단위라 autoswipe·RockStar·ZombieJump 모두 이 파일로 커버된다.
Play 스토어 등록정보의 개발자 웹사이트를 이 도메인의 URL
(`https://psyjs01.github.io/zombiejump-privacy-policy/`)로 넣으면 크롤러가 루트를 찾는다.
이 저장소 `public/app-ads.txt`의 사본은 참고용이다 (프로젝트 경로 쪽은 크롤링 대상 아님).

## 원본

내용 수정은 `ZombieJumpGodot/store/privacy_policy.html`에서 하고
이 저장소의 `public/privacy.html`에 복사해 푸시한다.
