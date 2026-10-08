# 최아인 CHOI AIN — Portfolio

Visual Designer · Art Director 포트폴리오 사이트 (GitHub Pages: https://ainxova.github.io)

## 폴더 구성

```
github-repo/
├── index.html   ← 사이트 전체 (HTML·CSS·JS가 한 파일에 들어 있음)
├── images/      ← 사이트에 쓰이는 모든 이미지·영상
├── fonts/       ← Pretendard 서브셋 폰트
├── files/       ← 이력서: ChoiAin_Resume.pdf(다크·크게 보기), ChoiAin_Resume_Print.pdf(화이트·다운로드), resume/(사이트 안 뷰어용 페이지 이미지)
└── README.md    ← 이 안내 파일
```

## GitHub에 올리는 방법

1. github.com/ainxova/ainxova.github.io 저장소로 들어갑니다.
2. **Add file → Upload files**를 누릅니다.
3. 이 폴더 안의 `index.html`, `images`, `fonts`, `files`, `README.md`를 **폴더 구조 그대로** 끌어다 놓습니다.
   (github-repo 폴더 자체가 아니라, 그 *안의 내용물*을 올려야 합니다.)
4. **Commit changes**를 누르면 1~2분 뒤 https://ainxova.github.io 에 반영됩니다.

> 파일 이름이나 폴더 위치를 바꾸면 이미지가 깨집니다. `index.html`은 `images/…`, `fonts/…`, `files/…` 경로를 그대로 참조합니다.
>
> 이력서를 새 버전으로 바꿀 때는 `files/` 안의 두 PDF와 `files/resume/resume-1~3.webp`를 **같은 이름으로** 덮어쓰면 됩니다. (사이트에 공개되는 웹용이라 전화번호·생년월일·주소는 빼 둔 버전입니다.)

## 참고

- 외부에서 불러오는 것: GSAP·ScrollTrigger·Lenis(애니메이션·스크롤 라이브러리). 인터넷 연결이 필요합니다.
- 아이콘은 index.html 안에 직접 들어 있습니다(외부 아이콘 라이브러리 사용 안 함).
- 영상은 webm + mp4 두 가지로 넣어 두었습니다(브라우저마다 재생 가능한 형식이 달라서).
