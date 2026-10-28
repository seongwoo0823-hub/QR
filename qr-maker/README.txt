QR 메이커 — 설치형(PWA) + 크롬 확장 프로그램

1) 웹에 올리기
이 폴더를 HTTPS 웹 호스팅에 그대로 올리면 휴대폰·PC에서 앱처럼 설치할 수 있어요.
  • Netlify Drop (app.netlify.com/drop) 에 폴더를 끌어다 놓기
  • GitHub 저장소에 올리고 Settings → Pages 켜기
  • Cloudflare Pages / Vercel 에 정적 사이트로 배포
사이트의 '설치' 버튼을 누르면 안드로이드 · 아이폰 · PC · 크롬 확장 설치 방법이 나와요.

2) 크롬 확장 프로그램
extension/qr-maker-extension.zip 이 사이트의 '크롬 확장' 탭에서 내려받아져요.
Chrome 웹 스토어에 올리면(개발자 등록비 1회 5달러) 클릭 한 번으로 설치되게 할 수 있어요.
스토어 주소가 생기면 index.html 안의  const STORE_URL = "";  에 주소를 넣어 주세요.

짧은 링크는 is.gd 무료 서비스로 만들어집니다. 인터넷 연결이 필요하고,
만들어진 짧은 링크는 is.gd에 공개적으로 기록됩니다.
