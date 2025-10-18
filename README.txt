# GodTour — 초간단 공식 홈페이지 (무료 호스팅용)

이 폴더는 **즉시 배포 가능한** 정적 사이트입니다. (index.html + styles.css)
한국어/영어 토글, 기본 OG 이미지/파비콘 포함.

## 1) 가장 빠른 방법 — GitHub Pages (완전 무료)
1. 깃허브 계정 만들기: https://github.com
2. 새 저장소(repo) 생성: 예) `gottour` (Public)
3. 이 폴더의 파일들을 업로드
4. 저장소 → Settings → Pages → **Branch: `main` / root** 선택 → Save
5. 1~2분 후 사이트 오픈: `https://<username>.github.io/gottour/`

- 커스텀 도메인 연결(선택): `Settings → Pages → Custom domain` 에 `godtour.ph` 같은 도메인 입력 후 DNS에 CNAME 추가.
  (도메인은 유료이나, 사이트 호스팅은 계속 무료)

## 2) 또 빠른 방법 — Netlify (무료)
1. https://app.netlify.com → Git로 연결 또는 **Drag & Drop**로 `index.html` 업로드
2. 즉시 `https://<project>.netlify.app` 주소 발급
3. 커스텀 도메인 연결은 Netlify에서 DNS 설정으로 가능 (도메인은 유료)

## 3) Cloudflare Pages (무료)
- GitHub 저장소 연결 → 자동 배포 → `*.pages.dev` 주소 부여

## 수정 포인트
- `index.html` 안 연락처/허가증 번호/회사 주소를 실제로 교체
- 이메일은 가능하면 회사 도메인(예: `hello@godtour.ph`) 사용 권장
- 예약 링크를 Google Form으로 연결하려면 `#contact` 섹션의 URL 교체

## KKday/클룩 심사 팁
- **회사 도메인**(예: `godtour.ph`)을 쓰면 신뢰도↑ (도메인 자체는 연 1만원대~)
- 사업자/허가증 스캔본은 별도 PDF 링크로 제공해도 좋음 (같은 repo에 올려 링크)
- 페이지 하단에 “Official company intro page” 문구 유지 권장

행운을 빌어요! 🚀