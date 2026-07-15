# JD 관리

채용 중(또는 마감된) 포지션들의 채용공고(JD, Job Description) 원문을 관리하는 폴더입니다.

## 구조

모든 포지션에 공통으로 들어가는 항목과, 포지션마다 다른 항목을 분리해서 관리합니다.

| 구분 | 항목 | 관리 방식 |
|---|---|---|
| 공통 (모든 포지션 동일) | 회사소개, 복리후생, 채용절차 | [`공통.md`](공통.md) 하나만 수정하면 됨 |
| 포지션별 (포지션마다 다름) | 직무소개, 담당업무, 자격요건, 우대사항 | [`포지션/`](포지션/) 폴더에 포지션당 파일 1개 |

실제 채용 사이트에 올릴 JD 전문은 "공통 3항목 + 해당 포지션의 4항목"을 합친 것입니다.

## 실제로 편집할 때는

이 폴더의 마크다운 파일은 **백업 및 검색용 사본**입니다. 실제로 포지션을 추가·삭제하거나 내용을 수정할 때는 [`../../HR-업무매뉴얼.html`](../../HR-업무매뉴얼.html)을 열어서 `09 · 채용 현황 관리` → **"JD 관리"**로 들어가 사용하는 것을 권장합니다.

- 포지션 추가/삭제, 그룹 지정, 순서 변경(드래그 앤 드롭)을 화면에서 바로 할 수 있습니다.
- 수정한 내용은 [파일로 저장]으로 내보낼 때 이 폴더의 내용도 함께 갱신해서 커밋해야 합니다 (수동 동기화).
- 포지션 상세 화면에서 "전체 JD 복사" 버튼으로 공통 항목 + 포지션 항목을 합친 전체 공고문을 바로 복사해 채용 사이트에 붙여넣을 수 있습니다.

## 현재 등록된 포지션 (27개, 그룹 미지정 — 필요 시 앱에서 그룹을 지정하세요)

| 포지션 |
|---|
| [`QA Engineer`](포지션/jd1_QA-Engineer.md) |
| [`SCM 매니저 (Supply Chain Management Manager)`](포지션/jd2_SCM-매니저.md) |
| [`AI 프로젝트 매니저 (AI Project Manager)`](포지션/jd3_AI-프로젝트-매니저.md) |
| [`구매 (Procurement / Purchasing Manager)`](포지션/jd4_구매.md) |
| [`법무행정 (Legal & Administration)`](포지션/jd5_법무행정.md) |
| [`기술관리 매니저 (Technology Management Manager)`](포지션/jd6_기술관리-매니저.md) |
| [`R&D 프로젝트 매니저 (R&D Project Manager)`](포지션/jd7_R&D-프로젝트-매니저.md) |
| [`재무회계 매니저 (Finance & Accounting Manager)`](포지션/jd8_재무회계-매니저.md) |
| [`경영기획 매니저 (Corporate Planning Manager)`](포지션/jd9_경영기획-매니저.md) |
| [`Field Sales`](포지션/jd10_Field-Sales.md) |
| [`AI Field Engineer`](포지션/jd11_AI-Field-Engineer.md) |
| [`사업기획 매니저 (Business Planning Manager)`](포지션/jd12_사업기획-매니저.md) |
| [`Product Strategy Manager`](포지션/jd13_Product-Strategy-Manager.md) |
| [`DevOps Engineer`](포지션/jd14_DevOps-Engineer.md) |
| [`AI Agent Development Engineer`](포지션/jd15_AI-Agent-Development-Engineer.md) |
| [`Vector Database Engineer`](포지션/jd16_Vector-Database-Engineer.md) |
| [`Storage System Software Engineer`](포지션/jd17_Storage-System-Software-Engineer.md) |
| [`SoC Firmware Engineer`](포지션/jd18_SoC-Firmware-Engineer.md) |
| [`SoC PKG / Board Hardware Engineer`](포지션/jd19_SoC-PKG--Board-Hardware-Engineer.md) |
| [`SoC Design Verification Engineer`](포지션/jd20_SoC-Design-Verification-Engineer.md) |
| [`SoC / RTL Design Engineer`](포지션/jd21_SoC--RTL-Design-Engineer.md) |
| [`System Architect`](포지션/jd22_System-Architect.md) |
| [`Vector Library Engineer`](포지션/jd23_Vector-Library-Engineer.md) |
| [`Firmware Software Engineer`](포지션/jd24_Firmware-Software-Engineer.md) |
| [`Device Driver Software Engineer`](포지션/jd25_Device-Driver-Software-Engineer.md) |
| [`Optimization Engineer`](포지션/jd26_Optimization-Engineer.md) |
| [`LLM Engineer`](포지션/jd27_LLM-Engineer.md) |

⚠️ 이 목록은 이 문서를 만든 시점(2026-07-14) 기준입니다. 실제 최신 포지션 목록·그룹 구성은 항상 앱(HR-업무매뉴얼.html)이 기준입니다.
