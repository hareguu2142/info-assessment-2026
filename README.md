# 2026 정보 과정형평가 안내 사이트

빌드 과정 없이 GitHub Pages에 바로 올릴 수 있는 정적 사이트입니다.

```
index.html               안내(홈)
vibe-coding.html         예시 ① 바이브코딩 (과정 기록 + 결과물 실행)
future-society.html      예시 ② 미래사회상
examples/incline-sim-v1.html   바이브코딩 결과물 원본(1차, 수정하지 않음)
assets/style.css         공통 스타일
assets/problem-incline.png     기준 문제 이미지
.nojekyll                Jekyll 처리 끄기
```

## 배포
1. GitHub에서 새 저장소를 만들고 이 폴더의 파일을 모두 올립니다.
2. 저장소 **Settings → Pages → Build and deployment**에서 Source를 `Deploy from a branch`, Branch를 `main` / `(root)`로 지정합니다.
3. 1~2분 뒤 `https://<아이디>.github.io/<저장소이름>/` 에서 확인합니다.
