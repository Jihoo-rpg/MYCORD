# Mycord

1. Firebase 설정을 index.html의 firebaseConfig에 붙여넣기
2. npm install
3. npm start            → 앱 실행
4. npm run dist:mac     → dist/ 폴더에 .dmg (맥에서)
   npm run dist:win     → dist/ 폴더에 .exe (윈도우에서)
   또는 GitHub에 올리면 Actions가 .exe와 .dmg를 자동으로 만들어줌

## 다운로드 사이트 (GitHub Pages)
- 저장소 Settings → Pages → Branch: main / 폴더: /docs → Save
- 사이트 주소: https://아이디.github.io/저장소이름/
- main에 올릴 때마다 Actions가 설치 파일을 만들어 Releases에 올리고, 사이트 버튼이 자동으로 최신 파일을 가리킴
