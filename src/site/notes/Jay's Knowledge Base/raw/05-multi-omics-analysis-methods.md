---
{"dg-publish":true,"permalink":"/jay-s-knowledge-base/raw/05-multi-omics-analysis-methods/","dg-note-properties":{}}
---


# 장내 미생물 다중 오믹스 분석 기술

출처: Duan et al. (2025) "Advances in multi-omics integrated analysis methods based on the gut microbiome" — Frontiers in Microbiology

## 주요 시퀀싱 기술

### 16S rRNA 앰플리콘 시퀀싱
- 세균 유전자의 보존 영역을 표적으로 미생물 분류
- V4 영역이 가장 빈번하게 타겟팅 — 높은 가변성과 종 수준 해상도
- V3-V4 (~460bp): Illumina 주로 사용
- 전장(full-length, ~1,480bp): Oxford Nanopore(ONT) 가능 → 더 정밀한 세균 프로파일

### 샷건 메타게노믹스(Shotgun Metagenomics)
- 환경에서 직접 채취한 미생물의 전체 게놈 시퀀싱
- 16S 대비 더 높은 분류학적 해상도와 게놈 정보 제공
- 기능적 잠재력(대사 경로 등) 파악 가능

### 시퀀싱 플랫폼 비교 (2025년 연구)
- **Illumina**: 높은 처리량, 비용 효율적, 대규모 프로젝트에 적합
- **ONT(Nanopore)**: 전장 16S 시퀀싱 가능, 더 포괄적인 세균 프로파일, 비용 더 높음
- 두 플랫폼 간 민감도/특이도 차이 있음 — 읽기 길이 차이에서 기인

### 최신 방법론 개선 (2025)
- V1-V3 또는 V6-V8 영역의 직접 결합(direct joining) 방법 → 페어드엔드 리드 병합 대비 분류학적 해상도 향상

## 분석 도구/파이프라인

| 도구 | 특징 |
|------|------|
| QIIME 2 | 전처리, 필터링, 클러스터링, 시각화. 플러그인 확장 가능. 16S/18S/메타게놈 분석 |
| MOTHUR | 종 풍부도 분석, 군집 생태학 연구 |
| Kraken | k-mer 기반 빠른 분류. 대규모 데이터셋에 적합 |
| MetaPhlAn | 메타게놈 계통분석 특화 |

## 다중 오믹스 통합 분석

### 통합 전략
- **숙주 게놈 + 미생물**: miGWAS 방법론 — 숙주 유전 변이와 미생물 구성의 상관관계
- **대사체(Metabolomics)**: SCFAs, 담즙산, 트립토판 대사물 등 미생물 대사산물 프로파일링
- **메타단백체(Metaproteomics)**: 미생물 단백질 발현 분석
- **전사체(Transcriptomics)**: 유전자 발현 패턴 분석

### 통계적 고려사항
- 마이크로바이옴 데이터는 구성적(compositional) 특성 → 전통적 통계 방법 적용에 제약
- 전문화된 통계 방법 필요 (예: ALDEx2, ANCOM, DESeq2)
