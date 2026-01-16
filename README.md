# ROF Video Source - 모바일 갤러리 웹앱

모바일 환경에서 이미지와 영상을 스크롤하며 볼 수 있는 원 페이지 웹앱입니다.

## 설치 방법

```bash
npm install
```

## 실행 방법

```bash
npm start
```

서버가 `http://localhost:3000`에서 실행됩니다.

## 미디어 파일 추가

`public/media/` 폴더에 다음 파일들을 추가하세요:

- `image1.jpg` - 첫 번째 이미지
- `image2.jpg` - 두 번째 이미지
- `image3.jpg` - 세 번째 이미지
- `video1.mp4` - 영상 파일

## 캡션 수정

`public/index.html` 파일에서 각 `<p class="caption">` 태그의 내용을 수정하면 됩니다.

## 구조

```
rof-video-source/
├── server.js          # Node.js 서버
├── package.json       # 의존성 관리
├── public/
│   ├── index.html     # 메인 HTML
│   ├── style.css      # 스타일시트
│   └── media/         # 이미지/영상 폴더
│       ├── image1.jpg
│       ├── image2.jpg
│       ├── image3.jpg
│       └── video1.mp4
└── README.md
```

