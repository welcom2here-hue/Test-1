# deoworks 블록 백업 (blockmaker)

식스샵 Pro 테마 **Grid "deoworks 1호"** (themeId `6a97a7931b0eec7792dea057`)의
커스텀 블록을 내려받은 백업입니다. 각 블록은 소스(`.html`)와 설정(`.json`)으로 나눠 저장했습니다.

- `.html` — 블록 소스(`<style>`/`<template>`/`<script>`/`<data>`). blockmaker `content` 원본.
- `.json` — `_id`, `title`, `tags`, `property`(기본값), `settings`(에디터 패널 정의).

수정 후 반영하려면 해당 `_id`로 `blockmaker_update_block`(content=해당 .html, settings/property=해당 .json)을 호출하면 됩니다.

## 블록 목록 (7개)

| 파일 | 블록명 | _id | tags |
|------|--------|-----|------|
| `deoworks-header` | deoworks 헤더 | 6a9f2cec08e4f1b63c629a38 | HEADER, MENU |
| `deoworks-hero-earthwork` | 데오웍스 히어로 (토목 기초공사) | 6a9bf48e08e4f1b63c61174c | MAIN_BANNER |
| `deoworks-hero-original` | deoworks 히어로 (기본/보관) | 6a98924ee0020b1677a8c642 | MAIN_BANNER |
| `deoworks-worktypes-grid` | deoworks 공사종류 그리드 | 6a9f34d908e4f1b63c629a4a | INFORMATION, GALLERY |
| `deoworks-projects-preview` | deoworks 홈 3 - 시공 실적 프리뷰 | 6aa0763908e4f1b63c65d381 | GALLERY, INFORMATION |
| `deoworks-product-supplement` | 보조 설명 (상품상세 전용) | 6aa00a7108e4f1b63c65b56d | PRODUCT |
| `deoworks-footer` | deoworks 푸터 | 6a989017e0020b1677a8c609 | FOOTER |

> 참고: 요청은 "3개"였지만 실제 테마에는 7개 블록이 있어 전부 백업했습니다.
> `deoworks-hero-earthwork`가 현재 Home 히어로에 적용된 블록이고,
> `deoworks-hero-original`은 교체 전 기본 히어로(보관용)입니다.
