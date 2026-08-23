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

## app-ads.txt 주의

`app-ads.txt`는 사양상 개발자 웹사이트 도메인의 루트에서 크롤링된다.
프로젝트 페이지(`psyjs01.github.io/zombiejump-privacy-policy/`)에 두면
`psyjs01.github.io/app-ads.txt`를 찾는 크롤러가 인식하지 못할 수 있다.
AdMob의 app-ads.txt 검증이 필요해지면 사용자 사이트 저장소(`psyjs01.github.io`)
루트에 두는 것을 검토한다 (autoswipe·RockStar·ZombieJump 모두 pub-8943982547557856
한 줄로 충분).

## 원본

내용 수정은 `ZombieJumpGodot/store/privacy_policy.html`에서 하고
이 저장소의 `public/privacy.html`에 복사해 푸시한다.
