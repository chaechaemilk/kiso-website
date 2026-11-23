# UB KISO 웹사이트

University at Buffalo 한인 유학생 커뮤니티 KISO의 공식 웹사이트.

## 폴더 구조

```
index.html      사이트 내용 (글, 임원진, 이벤트, 동아리)
css/style.css   디자인 (색, 글꼴, 배치)
images/         로고, 포스터, 동아리 그림, 임원 사진
```

## 자주 하는 수정

- **글 고치기**: `index.html`에서 해당 문장을 찾아 바꾸기
- **색 바꾸기**: `css/style.css` 맨 위 `:root` 안의 색 코드
- **임원 사진 넣기**: `images/`에 사진 추가 → `index.html`의 이니셜 `<div ...>JS</div>`를
  `<img class="officer-photo" src="images/파일이름.jpg" alt="이름">`으로 교체
- **이벤트 추가**: `index.html`의 `<article class="event">` 블록 하나를 복사해서 내용만 바꾸기
- **건의함**: `index.html`에서 `건의함 구글폼` 검색 → 링크 교체 (주소 끝이 `/edit`이 아니라 `/viewform`이어야 함)

## 배포

GitHub 저장소에 올리면 Cloudflare Pages가 자동으로 사이트를 업데이트함.
