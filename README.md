# 📰 AI 데일리 브리프 (7주 단기 AI 뉴스레터)

GitHub Pages의 기본 Jekyll 엔진을 활용하여 별도의 빌드 도구나 Node.js 환경 없이 작동하는 초경량 반응형 뉴스 웹사이트입니다.

---

## 🚀 GitHub Pages 1분 활성화 방법

1. 이 저장소를 본인의 GitHub 저장소에 푸시(또는 업로드)합니다.
2. GitHub 저장소 상단 탭에서 **Settings** → 좌측 메뉴 **Pages**로 이동합니다.
3. **Build and deployment** 항목의 **Source**를 **Deploy from a branch**로 설정합니다.
4. **Branch**를 `main` (또는 `master`), 폴더를 `/ (root)`로 선택하고 **Save**를 누릅니다.
5. 1~2분 후 상단에 표시되는 배포 주소(`https://<username>.github.io/...`)로 접속하면 사이트가 열립니다.

> **참고 (`_config.yml` 설정)**:  
> - 저장소 이름이 `<username>.github.io`인 경우: `baseurl: ""`  
> - 저장소 이름이 프로젝트명(예: `AINews`)인 경우: `baseurl: "/AINews"`로 설정해 주세요.

---

## ✍️ GitHub 웹 브라우저에서 새 글 발행하기 (노코드 가이드)

로컬 개발 환경(터미널, VS Code 등)을 켤 필요 없이, **스마트폰이나 웹 브라우저의 GitHub 화면**에서 바로 새 글을 작성하고 즉시 발행할 수 있습니다.

1. 저장소의 `_posts/` 폴더로 이동합니다.
2. 우측 상단의 **Add file** → **Create new file**을 클릭합니다.
3. 파일명 규칙에 맞추어 파일명을 입력합니다:
   - 형식: `YYYY-MM-DD-제목.md`
   - 예시: `2026-10-01-week-2-prompt-engineering.md`
4. 파일 내용 상단에 아래 **Front-matter 메타데이터**를 붙여넣고 글 내용을 작성합니다:

```markdown
---
layout: post
title: "제목"
date: 2026-00-00 09:00:00 +0900
category: "AI 도구"
read_time: "0분"
description: "설명"
---

여기에 본문 내용을 마크다운으로 편하게 작성하세요!
```

5. 페이지 하단의 녹색 **Commit changes...** 버튼을 누르면 끝입니다!
   - 약 1~2분 후 GitHub Pages가 자동으로 사이트를 재빌드하여 새 글이 메인 화면 맨 위에 발행됩니다.
