# 달빛출판사 홈페이지

GitHub Pages로 배포되는 정적 홈페이지입니다. 서버·DB 없이 파일만 올리면 동작합니다.

## 파일 구성

| 파일 | 설명 |
|---|---|
| `index.html` | 홈 (히어로 + 대표작 + 문의) |
| `works.html` | 작품 목록 |
| `about.html` | 출판사 소개 + 연락처 |
| `style.css` | 전체 디자인 (색·폰트·레이아웃) |

## 수정 방법

- **출판사 이름**: 세 HTML 파일의 `달빛출판사` / `Moonlit Books` 를 찾아 교체
- **색상**: `style.css` 맨 위 `:root` 변수만 수정 (예: `--accent`)
- **작품 추가**: `works.html` 의 `<a class="card">…</a>` 한 묶음을 복사해서 내용만 교체
- **연락처**: `contact@example.com`, 전화, 주소 교체

## 배포

`main` 브랜치에 push하면 GitHub Pages가 자동으로 갱신합니다.
