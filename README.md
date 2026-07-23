# publicRepo — 공개 문서 호스팅

Gnomonn 앱들의 **공개 정적 문서**(개인정보처리방침 등)를 GitHub Pages 로 서빙하는 저장소.
앱 소스는 별도 비공개 저장소에서 관리하고, 여기엔 공개돼도 되는 문서만 둔다.

## 구조
- `docs/privacy/<app-slug>.html` — 앱별 개인정보처리방침
- `docs/privacy/_template.html` — 새 앱용 템플릿

## GitHub Pages
- Settings → Pages → Source: `main` 브랜치 `/docs` 폴더.
- 공개 URL: `https://gnomonn.github.io/playstore_public/privacy/<app-slug>.html`

## 현재 문서
- Blurt: `docs/privacy/blurt.html`
- Reading Minute (Clock & Words): `docs/privacy/reading-minute.html`
- Dynamic Chess: `docs/privacy/dynamic-chess.html`
