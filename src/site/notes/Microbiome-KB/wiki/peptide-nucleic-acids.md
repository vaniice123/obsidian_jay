---
{"dg-publish":true,"permalink":"/microbiome-kb/wiki/peptide-nucleic-acids/","dg-note-properties":{}}
---

# 펩타이드 핵산(Peptide Nucleic Acids, PNA)

펩타이드 핵산(PNA)은 DNA/RNA의 당-인산 골격 대신 폴리아마이드(pseudopeptide) 골격을 가진 합성 핵산 유사체이다. 뉴클레아제와 프로테아제에 대한 높은 저항성, DNA/RNA에 대한 강력한 결합력(높은 Tm), 서열 특이성이 장점이며, 유전자 발현 조절, 진단, 유전체 편집 보조 도구로 활용된다. 양이온 변형(cationic modification)을 통해 이중가닥 DNA 침투력과 자기결합(self-duplex) 문제를 개선하는 연구가 활발하다.

---

## 핵심 특성

- **골격**: N-(2-aminoethyl)glycine 반복 단위 — 전하 중성
- **결합**: Watson-Crick 염기쌍으로 DNA/RNA에 결합, Tm이 DNA/DNA보다 높음
- **안정성**: 뉴클레아제, 프로테아제 모두에 저항
- **서열 특이성**: 단일 mismatch에 대한 민감도가 DNA 프로브보다 높음

---

## 작용 기전

### 유전자 발현 억제
- mRNA 결합 → 번역 억제 (steric blocking)
- 표적 서열 위치(AUG 개시 코돈 vs 코딩 영역)에 따라 억제 효율 차이 (raw/410)

### 이중가닥 DNA 인식
- Strand invasion 또는 double-duplex invasion 방식으로 dsDNA 결합
- 양이온 변형 PNA가 double-duplex 형성으로 dsDNA 인식 가능 (raw/335)
- **Cationic guanine**: 양전하 뉴클레오베이스로 dsDNA 친화도 향상, 자기결합 억제 (raw/338)

### 유전체 편집 보조
- **PNA-DNAzyme**: PNA가 dsDNA를 열어 DNAzyme의 단일가닥 절단 가능하게 함 → 높은 서열 정확도의 유전체 편집 (raw/336)
- 기존 CRISPR의 off-target 문제를 보완하는 대안적 접근

---

## 화학적 변형

| 변형 | 효과 | 참고 |
|------|------|------|
| **γ-변형 (miniPEG 등)** | 수용성, 세포 투과성 개선 | raw/397 |
| **양이온 변형 (cationic bases)** | dsDNA 침투, self-duplex 억제 | raw/338, raw/445 |
| **CPP 접합 (cell-penetrating peptide)** | 세포 내 전달 향상 | raw/433 |
| **올리고뉴클레오타이드 조립** | CPP-PNA를 올리고에 조립하여 전달 | raw/433 |

- 양이온/아미노알킬 변형 염기가 하이브리드화 강도를 촉진하고 세포 투과성 개선 (raw/445)
- 최근 화학 변형 리뷰: 치환기별 결합력, 세포 흡수, in vivo 효능 비교 (raw/397)

---

## 응용 분야

### 치료제
- **MMP-1 억제**: 토피컬 PNA ASO 적용으로 피부 노화 방지 가능성 (raw/372)
- **암 바이오나노기술**: PNA 기반 진단 및 치료 나노구조체 (raw/401)
- **면역 조절**: 구형 핵산(spherical nucleic acids) 내 PNA 활용 (raw/427)

### 진단
- **초고감도 ELISA**: 비경쟁적 하이브리드화-라이게이션 PNA 기반 분석법 개발 (raw/435)

### 유전자 조절
- PNA binding-mediated gene regulation: 전사, 번역, 스플라이싱 다단계 조절 가능 (raw/334)
- 치료제 및 유전체 편집 도구로서의 잠재력 리뷰 (raw/376)

---

## 관련 wiki 링크

- [[Microbiome-KB/wiki/antisense-oligonucleotides\|antisense-oligonucleotides]] — ASO: PNA와 비교되는 핵산 치료제 플랫폼

## 출처

- `raw/334` (PNA 유전자 조절), `raw/335` (double-duplex invasion), `raw/336` (PNA-DNAzyme)
- `raw/338` (cationic guanine), `raw/372` (MMP-1 토피컬), `raw/376` (PNA 치료제/편집 리뷰)
- `raw/397` (화학 변형 리뷰), `raw/401` (암 바이오나노), `raw/410` (세포 내 유전자 억제)
- `raw/427` (면역 조절 SNA), `raw/433` (CPP-PNA 전달), `raw/435` (PNA ELISA)
- `raw/445` (양이온 PNA 하이브리드화)
