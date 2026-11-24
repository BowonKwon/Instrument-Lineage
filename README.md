# 악기의 계보 · Lineages of instruments

악기가 어디서 와서 어떻게 바뀌고 이어졌는지를 문서·기록·그림으로 따라가는 사이트입니다. 장은 셋으로 계획했고, 지금은 ③장 『악학궤범』을 먼저 공개합니다. 비상업 교육용이며, 독립 검증을 거쳤지만 아직 **탐색판**입니다.

A site that follows where instruments came from and how they changed and carried on, through documents, records and pictures. Three chapters are planned; chapter 3, *Akhak gwebeom*, is published first. It is noncommercial and educational; it has been checked independently but is still an **exploratory edition**.

- 사이트 · Site: https://bowonkwon.github.io/Instrument-Lineage/

## 장 · Chapters

| 장 · Chapter | 상태 · Status |
|---|---|
| ③ 『악학궤범』 — 1493년의 악기 그림책, 그 뒤 · *Akhak gwebeom*: a 1493 picture book of instruments, and what came after | 탐색판 0.2.1 · exploratory edition 0.2.1 |
| ① 특허와 발명 · Patents and invention | 준비 중 · in preparation |
| ② 관현악 편성 · Orchestration | 준비 중 · in preparation |

## ③장에서 다루는 것 · What chapter 3 covers

- 1493년 『악학궤범』에 그림으로 실린 64조목(악기 58, 의물 6)이 지금 어떻게 쓰이는지 · how the 64 entries pictured in the 1493 book (58 instruments, 6 ritual objects) are used today
- 1610년 판, 1655년 인출, 1743년 책, 경자년 신비본, 1933년 영인본으로 이어진 판본의 내력 · the history of its editions: 1610, the 1655 printing, the 1743 copy, the gyeongja copy and the 1933 facsimile
- 아홉 권의 차례와 권별 면 수 · the nine books and their page counts
- 문서가 정한 때, 만들어진 때, 쓰이게 된 때의 어긋남 — 생황, 공후, 슬 그림의 줄 · the gap between record, making and use: the mouth organ, the harp gonghu, the strings in the picture of the zither seul

## 데이터 · Data

| 파일 · File | 내용 · Contents |
|---|---|
| `data/akhak-64-items.csv` | 64조목: 부, 한글·한자·로마자 이름, 지금 상태(국립국악원 국악사전 문구를 줄인 것 — 의물 6은 사전 출처 없음, 항목이 없는 3은 검색 결과), 상태의 출처 · the 64 entries: section, Korean, hanja and romanized names, present status (condensed from the National Gugak Center's encyclopedia — no encyclopedia source for the 6 ritual objects; the search result for the 3 with no entry), source |
| `data/akhak-volumes.csv` | 아홉 권의 첫 면·끝 면·면 수(면 번호는 1~3권 1610년 판, 4~6권 1743년 책 둘째 책 — 1610년 판과 같음, 7~9권 1743년 책 셋째 책) · first page, last page and page count of the nine books (page numbers: books 1–3 from the 1610 edition, books 4–6 from the second volume of the 1743 copy, the same as the 1610 edition, books 7–9 from the third volume of the 1743 copy) |

## 확인한 방법 · How it was checked

- 판본은 원판 이미지(국립중앙도서관 소장 목판본, 1933년 영인본)와 장서각 소장본에서 고른 면들을 맞대어 확인했습니다. 권별 면 수는 각 권의 첫 면·끝 면 번호로 셌습니다(면 번호의 출처는 권마다 데이터 설명과 그림 설명에). · Editions were checked by comparing selected pages in images of the woodblock copy in the National Library of Korea, the 1933 facsimile and the copy in the Jangseogak library. Page counts per book are taken from the first and last page numbers of each book (the source of the page numbers is given per book in the data description and the chart notes).
- 한문은 원문과 함께 싣고 직접 옮겼습니다. 판독이 어려운 글자와 주장의 출처는 다른 AI 모델이 원자료와 따로 대조했고, 그 지적을 반영했습니다. · Classical Chinese passages are given with the original text and translated directly. Hard-to-read characters and the sources of the claims were checked separately against the sources by another AI model, and its findings were incorporated.
- 이 사이트는 AI 도구의 도움을 받아 만들고 엮은이가 원자료로 검증했습니다. · This site was built with the help of AI tools and verified against the sources by the editor.

## 알려 주세요 · Corrections

틀린 곳은 [이슈](https://github.com/BowonKwon/Instrument-Lineage/issues)로 알려 주시면 고칩니다. 책과 면을 함께 적어 주시면 바로 확인할 수 있습니다.

Please report errors through the [issues](https://github.com/BowonKwon/Instrument-Lineage/issues). Giving the volume and page makes a report quick to check.

## 판 · Versions

- **0.2 탐색판 · exploratory edition** (2026-11) — ③장 『악학궤범』 한국어·영어. · Chapter 3, *Akhak gwebeom*, in Korean and English.
- **0.2.1** (2026-11-24) — 두 그림(권별 면 수, 64조목의 지금)의 설명을 「한눈에」 「그림 보는 법」 「숫자 하나 읽어 보기」 「잘못 읽기 쉬운 것」 「낱말 풀이」 같은 이름 붙은 단락으로 풀어 씀. 좁은 화면에서는 면 수 막대그림을 권 이름이 막대 위에 오는 모양으로 보여 줌(글자가 작아지고 겹치던 것, 영어판 권 이름이 잘리던 것을 고침). 영어판 칸 그림의 칸 폭을 넓힘. 막대그림에 세로(권) 표시를 더함. 면 번호를 어느 책에서 셌는지 권 범위별로 밝힘. 공통 스타일(설명 단락·범례, 좁은 화면 기준 480px→560px)이 바뀜. 값과 분류는 그대로. 회색 범례 이름을 「지금 쓰이지 않음」에서 「기록만(지금 쓰임 확인 안 됨)」으로, 황토색을 「끊겼다가 복원」에서 「복원·재현」으로 바꾸고 칸 풀이·요약·정리·자료와 방법의 해당 문장을 맞춤. · The explanations of the two charts (pages per book, the 64 entries today) are rewritten as named paragraphs such as In short, How the chart works, Reading one value, Easy to misread and Terms. On narrow screens the page-count chart puts the book names above the bars (text had become small and overlapping, and English book names were cut off). Wider cells in the English entry chart. A vertical (book) label in the page-count chart. Which volume the page numbers come from is now stated for each range of books. The shared styles changed (explanation paragraphs and keys; the narrow-screen breakpoint moved from 480px to 560px). Values and the grouping of cells are unchanged. The gray key is renamed from “Not in use today” to “Record only (present use not confirmed)” and the ocher key from “Lost, then restored” to “Restored or reconstructed,” with the cell hovers, summaries, closing section and sources note changed to match.

## 라이선스 · License

[LICENSE.md](LICENSE.md)
