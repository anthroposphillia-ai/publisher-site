# VEHICLE MAD TODDLER — 홈페이지

Independent Publisher. GitHub Pages로 배포되는 정적 원페이지 사이트입니다.

**주소**: https://anthroposphillia-ai.github.io/publisher-site/

## 파일 구성

| 파일 | 설명 |
|---|---|
| `index.html` | 전체 페이지 (Hero / About / Books / Projects / Contact) |
| `style.css` | 디자인 전체 (색·폰트·레이아웃) |
| `favicon.svg` | 브라우저 탭 아이콘 |

## 수정 방법

- **색상**: `style.css` 맨 위 `:root` 의 `--accent`(포인트색), `--paper`(배경), `--ink`(글자)만 수정
- **문구**: `index.html` 의 각 `<section>` 안 텍스트 교체
- **책 목록**: `.books` 안의 `.book` 카드 수정·추가
- **프로젝트**: `.projects` 안의 `<li>` 추가·수정
- **연락처**: `.clink` 의 이메일·인스타·깃허브 주소 교체

## 배포

`main` 브랜치에 push하면 GitHub Pages가 자동으로 갱신됩니다 (1~2분).
