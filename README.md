# Bheom Seok Kim 개인 웹사이트 (Quarto)

## 처음 할 일
1. `profile.jpg` (프로필 사진)과 `cv.pdf` (CV)를 이 폴더에 넣기
2. `_quarto.yml`의 `bskim89`를 본인 GitHub 아이디로 바꾸기
3. `index.qmd`에서 LinkedIn / Google Scholar 주소를 넣고 주석(#) 지우기

## 미리보기 / 빌드
- 미리보기: `quarto preview`
- 빌드: `quarto render` → `docs/` 폴더 생성

## 공개 (GitHub Pages)
1. GitHub에 `bskim89.github.io` 저장소 생성
2. 이 폴더 전체(docs 포함)를 push
3. Settings → Pages → Deploy from a branch → `main` / `/docs`

## 수정
`.qmd` 수정 → `quarto render` → commit & push
