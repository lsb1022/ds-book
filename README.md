# 자료구조와 알고리즘 — 교재 + 빈칸 연습

정적 사이트(백엔드 없음). GitHub Pages에 그대로 올리면 동작합니다.

- `/` — 교재 (`index.html`이 `book.json`과 `img/`를 불러옴)
- `/summary/` — 장별 요약 (교재 목차와 같은 순서, 각 항목의 "원문"으로 교재 해당 절로 이동)
- `/drills/` — 빈칸 연습 모음
- `/exam/` — 시험 대비 (모의고사, 교재 연습문제)

## GitHub Pages 배포
1. 새 저장소를 만들고 이 폴더의 파일을 전부 저장소 루트에 올린다 (`.nojekyll` 포함).
2. Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: `main` / `(root)` → Save.
3. 1~2분 뒤 `https://<아이디>.github.io/<저장소이름>/` 에서 열린다.

## 로컬에서 보기
`book.json`을 fetch로 불러오므로 파일을 더블클릭하면 안 되고, 서버를 띄워서 연다.

```
python3 -m http.server 8000
# http://localhost:8000
```

진행 기록(푼 문제, 읽던 위치, Py/C++ 설정)은 브라우저 localStorage에 저장된다.
