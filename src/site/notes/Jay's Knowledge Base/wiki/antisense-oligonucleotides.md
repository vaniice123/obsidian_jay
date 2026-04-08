---
{"dg-publish":true,"permalink":"/microbiome-kb/wiki/antisense-oligonucleotides/","dg-note-properties":{}}
---

# 안티센스 올리고뉴클레오타이드(Antisense Oligonucleotides, ASO)

안티센스 올리고뉴클레오타이드(ASO)는 표적 mRNA에 상보적으로 결합하여 유전자 발현을 조절하는 합성 단일가닥 핵산 치료제이다. RNase H 매개 분해, 스플라이스 스위칭(exon skipping/inclusion), 번역 억제 등 다양한 기전으로 작용하며, FDA 승인 약물 다수가 존재한다. 화학적 변형(PS backbone, 2'-MOE, LNA, PMO 등)을 통해 안정성, 결합력, 약동학을 개선하는 것이 핵심 과제이다.

---

## 작용 기전

### RNase H 매개 분해 (Gapmer)
- DNA 중심부(gap) + 변형 뉴클레오타이드 양 날개(wings)
- RNA/DNA 하이브리드 형성 → RNase H1이 표적 mRNA 절단
- 간독성 위험: 고친화 gapmer에서 RNase H1 의존적 간독성 보고 (raw/403)

### 스플라이스 스위칭
- 엑손 스키핑(exon skipping): DMD 치료제 (viltolarsen, eteplirsen) — 돌연변이 엑손 건너뛰기로 truncated dystrophin 생산 (raw/384, raw/391)
- Cryptic exon 억제: TDP-43 기능 상실 시 UNC13A, STMN2의 cryptic exon 포함 → ASO로 교정 가능 (raw/446)

### 유전자 발현 활성화 (saRNA)
- Small activating RNA → 표적 유전자 전사 촉진 (raw/408)
- 기존 억제 중심 접근과 반대 방향의 치료 전략

---

## 화학적 변형

| 변형 | 특성 | 대표 약물 |
|------|------|-----------|
| **PS (Phosphorothioate)** | 뉴클레아제 저항, 혈장 단백질 결합 | 대부분의 ASO |
| **2'-MOE** | Tm 상승, 독성 감소 | Nusinersen, Inotersen |
| **PMO (Morpholino)** | 전하 중성, 면역 반응 최소화 | Viltolarsen, Eteplirsen |
| **LNA** | 매우 높은 결합력, 간독성 주의 | — |
| **cEt** | LNA 유사, 독성 개선 | — |

- PS-ASO의 세포 단백질 결합이 치료 효과와 독성 모두에 영향 → 화학적 변형으로 단백질 결합 프로파일 조절 가능 (raw/432)
- 차세대 ASO: 세포 내 흡수 역학(kinetics)과 트래피킹 기전이 화학 구조에 따라 상이 (raw/466)

---

## FDA 승인 ASO 치료제

- **Nusinersen** (Spinraza): SMA, 척수강 내 투여 (raw/467)
- **Inotersen** (Tegsedi): hATTR, 피하주사 (raw/420)
- **Viltolarsen** (Viltepso): DMD 엑손 53 스키핑 (raw/384)
- **Inclisiran**: PCSK9 siRNA, 피하주사, LDL-C 저하 (raw/416)
- 2017-2019년 사이 다수의 올리고뉴클레오타이드 치료제 FDA 승인 (raw/394)

---

## ALS 치료제 개발

- **STMN2 교정**: TDP-43 핵 손실 → STMN2 cryptic exon 포함 → 비정상 polyadenylation → ASO로 정상 스플라이싱 회복 (raw/446, raw/354, raw/355)
- **UNC13A 교정**: ALS/FTD 위험 SNP가 TDP-43 결합 부위에 위치 → cryptic exon 포함 촉진 → ASO 치료 표적 (raw/328, raw/329, raw/352)
- **FUS 침묵**: FUS 돌연변이 ALS에서 ASO 매개 FUS 발현 감소 전략 (raw/430)
- **Ataxin-2 감소**: TDP-43 마우스 모델에서 수명 연장, 병리 감소 확인 (raw/359)
- ALS 임상 파이프라인 확대 추세 (raw/344, raw/415)

---

## 전달(Delivery) 과제

- **BBB 통과**: 종양 세포 유래 소포체(small apoptotic bodies)를 이용한 BBB 통과 ASO 전달 (raw/399)
- **경구 투여**: 경구용 PCSK9 ASO 개발 — 간 표적화의 새로운 가능성 (raw/464)
- **간외 조직(Extrahepatic)**: 지질 접합 RNAi — 간 이외 조직 전달 확대 (raw/461)
- **PK/PD 모델링**: Nusinersen CSF/혈장 PK (raw/467), Inotersen PK/PD (raw/420), FXI ASO 용량-활성 관계 (raw/426)

---

## 관련 wiki 링크

- [[Microbiome-KB/wiki/peptide-nucleic-acids\|peptide-nucleic-acids]] — PNA: ASO의 대안적 핵산 유사체
- [[Microbiome-KB/wiki/nav17-pain-therapeutics\|nav17-pain-therapeutics]] — Nav1.7 ASO/유전자 치료 전략

## 출처

- `raw/314` (PCSK9 ASO), `raw/356` (eSkip-Finder), `raw/358` (RNA 이차구조 ASO 설계)
- `raw/384` (Viltolarsen), `raw/391` (엑손 스키핑), `raw/393` (ASO 기술 리뷰)
- `raw/394` (FDA 승인 2017-19), `raw/396` (tau ASO), `raw/399` (BBB 전달)
- `raw/402` (ASO 화학 진화), `raw/403` (간독성), `raw/404` (암 스플라이스 스위칭)
- `raw/408` (saRNA), `raw/411` (혈장 단백질 상호작용), `raw/415` (ALS ASO)
- `raw/416` (Inclisiran), `raw/420` (Inotersen PK/PD), `raw/426` (FXI ASO PK/PD)
- `raw/430` (FUS ASO), `raw/432` (PS-ASO 화학 변형), `raw/441` (펩타이드-올리고 접합체)
- `raw/446` (STMN2 교정), `raw/462` (ASO 전망), `raw/464` (경구 ASO)
- `raw/466` (차세대 ASO 트래피킹), `raw/467` (Nusinersen PK), `raw/474` (비코딩 RNA 치료제)
