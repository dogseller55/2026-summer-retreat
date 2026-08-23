# 흩어진 글을 한자리에 모으며  
**2026 예은교회 하계수련회 기록집**

일흔두 편의 후기를 조별로 모아 엮은 기록입니다.

## 구성

| 파일 | 내용 |
|------|------|
| `index.html` | 표지 + 목차 |
| `preface.html` | 서문 |
| `01-udada.html` | 1조 우다다 — 우리 다시 다함께 |
| `02-ppudeut.html` | 2조 뿌듯 — 짐이 아니라 힘 |
| `03-jipjung.html` | 3조 집중 — 한계를 먼저 만난 조 |
| `04-meonjeo.html` | 4조 먼저 — 무엇을 먼저 할 것인가 |
| `05-hwanyeong.html` | 5조 환영 — 작은 풀장에서 |

## GitHub Pages에 올리는 방법

1. GitHub에서 새 저장소 만들기 (예: `2026-summer-retreat`)
2. 이 폴더의 파일들을 모두 업로드
3. 저장소 **Settings → Pages** 이동
4. Source를 `Deploy from a branch` → Branch를 `main` / `/ (root)` 선택 → Save
5. 몇 분 후 `https://dogseller55.github.io/2026-summer-retreat/` 로 접속 가능

## 카톡 미리보기(썸네일) 설정

1. `thumbnail.jpg` (또는 `.png`) 파일을 이 폴더에 넣기  
   - 권장 크기: **1200 × 630 px**
2. 모든 HTML 파일 안의  
   `https://dogseller55.github.io/2026-summer-retreat/thumbnail.jpg`  
   부분을 실제 주소로 바꾸기  
   (예: `https://yourname.github.io/2026-summer-retreat/thumbnail.jpg`)

카톡에서 링크를 보낼 때 제목·설명·이미지가 미리보기로 뜹니다.

## 썸네일 이미지 프롬프트

```
Minimal elegant book cover illustration for a Korean church summer retreat record book.
Soft paper-colored background (#F3F6F3).
Two thin parallel lines (like slacklines or wires over water) gently curving across the center in deep pine green (#2E5241).
Above the lines: Korean title in elegant serif "흩어진 글을 한자리에 모으며".
Below: smaller text "2026 예은교회 하계수련회 기록집".
Subtle soft watercolor texture, calm and warm atmosphere, no people, no clutter.
Clean, literary, high-quality, 1200x630 aspect ratio, soft natural lighting.
```

생성 후 `thumbnail.jpg`로 저장해서 저장소 루트에 넣으면 됩니다.

## 로컬에서 미리보기

```bash
cd 이폴더
python3 -m http.server 8000
```

브라우저에서 `http://localhost:8000` 접속.

---

엮은이: 방송실 이효진 안수집사  
2026. 8. 2 — 8. 6 · 당진
