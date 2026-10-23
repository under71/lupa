# Release notes · 릴리스 노트
Lupa on the [Mac App Store](https://apps.apple.com/app/id6789231809). Newest first.

## 2.0.2 — In App Review · 심사 중

- Copies of the same file are now folded into one row, so duplicates scattered across Downloads and backup folders no longer crowd out your results. Turn on "Show copies" in the filters to see each one.
- Duplicate report: see where copies pile up and how much space they take. Lupa never deletes files.
- Text inside mail files (.eml, .emlx, .mbox) is now searchable.
- New "Presentation" filter: show only slide decks (.ppt, .pptx, Keynote) in one click.
- Long documents are indexed up to the first 10,000 characters (was 5,000). After updating, only documents that were cut off are read again, and search keeps working meanwhile.
- Broader Hangul document support: HWPX and HWPML files saved with a .hwp extension are read, and distribution-protected HWP files can be found by their opening text.
- Fixed quoted phrases in content search (c:"exact phrase") returning no results.
- Refined AI agent connections: date conditions such as "last 7 days" are followed exactly, and agents are told when only the beginning of a long document is indexed. The text of distribution-protected documents is never passed to agents.

<details><summary>한국어</summary>

- 같은 파일의 사본을 한 줄로 접어 보여줍니다. 다운로드·백업 폴더에 흩어진 사본 때문에 결과가 같은 문서로 가득 차던 문제가 사라집니다. 필터의 "사본 펼치기"로 각각 볼 수도 있습니다.
- 사본 정리 리포트: 사본이 어디에 얼마나 쌓여 있는지 보여줍니다. 파일을 지우지는 않습니다.
- 메일 파일(.eml, .emlx, .mbox) 안의 내용도 검색됩니다.
- 상단 분류에 "프레젠테이션"을 추가했습니다. 발표자료(.ppt, .pptx, Keynote)만 한 번에 걸러 봅니다.
- 긴 문서는 앞 10,000자까지 색인합니다(이전 5,000자). 업데이트 후 잘려 있던 문서만 다시 읽으며, 그동안에도 검색은 그대로 됩니다.
- 한글 문서 지원을 넓혔습니다. 확장자만 .hwp인 HWPX·HWPML 문서를 읽고, 배포용 문서는 앞부분으로 찾을 수 있습니다.
- 내용 검색에서 따옴표로 묶은 구문(c:"위약금 조항")이 결과를 찾지 못하던 문제를 고쳤습니다.
- AI 에이전트 연결을 다듬었습니다. "최근 7일" 같은 날짜 조건을 정확히 따르고, 앞부분만 색인된 문서는 그 사실을 함께 알립니다. 배포용 문서의 본문은 에이전트에 넘기지 않습니다.

</details>

## 2.0.1 — 2026-09-21

- Apps come first. Search for an app by name and it appears at the top of the results.
- Better Google Drive and OneDrive support. A new quick-add button, and your existing index is kept even when the cloud app is closed or disconnected. Files that are only in the cloud are not downloaded during indexing.
- Text inside Obsidian canvases (.canvas) is now searchable.
- Search by folder name: turn on "Include folder names" in the filters.
- When filters hide results, Lupa tells you how many and lets you turn the filters off in one click.
- More accurate multi-word search: files that match every word come first, even when one word is very common.
- Improved AI agent connections: Aside can now be connected from Settings in one step, and a Claude Desktop connection issue is fixed.
- Stability fixes, including results redrawing whenever files changed and the iCloud Drive quick-add button not appearing.

<details><summary>한국어</summary>

- 앱을 먼저 보여줍니다. "노션", "크롬", "카카오"처럼 앱 이름을 검색하면 앱이 맨 위에 나옵니다. 한국어 이름이 없는 앱도 한국어로 찾을 수 있습니다.
- Google Drive·OneDrive 지원을 강화했습니다. 빠른 추가 버튼이 생겼고, 클라우드 앱이 꺼져 있거나 연결이 끊겨도 기존 색인을 그대로 지킵니다. 아직 내려받지 않은 파일은 인덱싱 중에 내려받지 않습니다.
- Obsidian 캔버스(.canvas) 안의 글도 검색됩니다.
- 폴더 이름으로도 찾을 수 있습니다. 필터의 "폴더명 포함"을 켜세요.
- 필터 때문에 결과가 가려지면 몇 개가 숨겨졌는지 알려주고, 바로 끌 수 있습니다.
- 여러 단어 검색이 더 정확해졌습니다. 흔한 단어가 섞여도 모두 일치하는 파일이 먼저 나옵니다.
- AI 에이전트 연결을 개선했습니다. 설정에서 한 번에 연결할 수 있는 대상에 Aside를 추가했고, Claude Desktop 연결 문제를 고쳤습니다.
- 파일이 바뀔 때마다 검색 결과 화면이 다시 그려지던 문제, iCloud Drive 빠른 추가가 보이지 않던 문제 등 여러 안정성 문제를 고쳤습니다.

</details>

## Earlier · 이전 버전

- **2.0** (2026-09-06) — AI agent integration: the app connects Claude Code / Claude Desktop in one click; `lupa-search --content` returns indexed text to agents without opening files; image OCR for screenshots and photos.
- **1.0.2** (2026-08-21) — Command-line tool `lupa-search` bundled with the app.
- **1.0.1** (2026-08-01) — Fixes after launch.
- **1.0** (2026-07-18) — First release.
