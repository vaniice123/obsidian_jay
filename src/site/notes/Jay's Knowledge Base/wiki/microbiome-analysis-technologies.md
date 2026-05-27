---
{"dg-publish":true,"permalink":"/jay-s-knowledge-base/wiki/microbiome-analysis-technologies/","dg-note-properties":{}}
---


# 마이크로바이옴 분석 기술(Microbiome Analysis Technologies)

마이크로바이옴 분석은 크게 마커 유전자 기반(16S rRNA)과 전체 게놈 기반(샷건 메타게노믹스)으로 나뉘며, 최근에는 대사체, 단백체, 전사체를 통합하는 다중 오믹스(multi-omics) 접근이 확대되고 있다.

## 마이크로바이옴 개념 정의

"마이크로바이옴(microbiome)"이라는 용어는 분야별 사용이 혼재되어 명확한 합의 정의가 부재했다. MicrobiomeSupport 프로젝트의 국제 전문가 패널은 마이크로바이옴을 단순한 미생물 집합(미생물군집, microbiota)이 아니라 **미생물 + 그들의 활동·대사산물·유전 요소 + 정의된 서식 환경(theatre of activity)을 포함하는 동적 상호작용계**로 재정의하고, 표준화·재현성 확보를 위한 모범 사례(best practices)를 제안하였다 ([[Jay's Knowledge Base/raw/31-berg-2020-microbiome-definition-re-visited-old-concepts-and\|Berg et al., 2020]]). 이 정의는 분석 설계 시 미생물 구성뿐 아니라 기능·환경 맥락을 함께 고려해야 함을 시사한다.

## 16S rRNA 앰플리콘 시퀀싱

- 세균 유전자의 보존 영역을 타겟으로 미생물 분류
- **V4 영역**: 가장 빈번하게 사용, 높은 가변성과 종 수준 해상도
- **V3-V4 (~460bp)**: Illumina 플랫폼 주로 사용
- **전장(~1,480bp)**: ONT(Nanopore) 가능 → 더 정밀한 세균 프로파일

### 장점
- 비용 효율적, 표준화된 프로토콜
- 대규모 코호트 연구에 적합

### 한계
- 종/균주 수준 해상도 제한적 (전장 시퀀싱으로 개선 중)
- 기능적 잠재력 파악 불가 (어떤 균이 있는지는 알지만, 무엇을 하는지는 모름)

### 분류학적 다양성 — 배양 의존 분석의 한계

배양 비의존 16S rRNA 시퀀싱은 인간 장내 미생물 다양성 이해의 전환점이었다. 건강한 성인의 대장 점막 여러 부위 및 분변에서 13,355개 원핵 rRNA 유전자 서열을 분석한 결과, **대부분의 서열이 미배양(uncultivated) 신규 미생물**에 해당했고, 개체 간 변이가 크며 점막과 분변 군집이 상이함이 밝혀졌다 ([[Jay's Knowledge Base/raw/92-eckburg-2005-diversity-of-the-human-intestinal-microbial-flo\|Eckburg et al., 2005, *Science*]]). 이는 배양 기반 방법이 실제 다양성의 일부만 포착한다는 점을 입증해 시퀀싱 기반 프로파일링 표준화의 출발점이 되었다.

## 샷건 메타게노믹스(Shotgun Metagenomics)

- 환경에서 직접 채취한 미생물의 **전체 게놈** 시퀀싱
- 16S 대비 더 높은 분류학적 해상도
- **기능적 정보** 제공: 대사 경로, 항생제 내성 유전자 등

### 장점
- 세균뿐 아니라 바이러스, 진균도 검출 가능
- 기능적 잠재력(유전자 기능) 파악

### 한계
- 비용 높음, 데이터 분석 복잡
- 숙주 DNA 오염 문제

## 시퀀싱 플랫폼 비교

| 플랫폼 | 읽기 길이 | 장점 | 한계 |
|--------|----------|------|------|
| **Illumina** | 짧은 리드 (V3-V4) | 높은 처리량, 비용 효율적 | 종 수준 해상도 제한 |
| **ONT(Nanopore)** | 긴 리드 (전장 16S) | 더 정밀한 세균 프로파일 | 비용 높음, 오류율 |

2025년 연구: V1-V3 또는 V6-V8 영역의 직접 결합(direct joining) → 페어드엔드 병합 대비 분류학적 해상도 향상

## 분석 도구/파이프라인

| 도구 | 용도 | 특징 |
|------|------|------|
| **QIIME 2** | 16S/18S/메타게놈 | 전처리~시각화, 플러그인 확장 |
| **MOTHUR** | 종 풍부도/군집 생태학 | 커뮤니티 분석 특화 |
| **Kraken** | 분류학적 분류 | k-mer 기반, 빠름, 대규모 데이터셋 |
| **MetaPhlAn** | 메타게놈 계통분석 | 메타게놈 특화 |

## 다중 오믹스 통합

| 오믹스 | 분석 대상 | 마이크로바이옴 적용 |
|--------|----------|-------------------|
| **메타게노믹스** | DNA/유전자 | 미생물 종 구성, 기능 유전자 |
| **대사체(Metabolomics)** | 대사산물 | [[Jay's Knowledge Base/wiki/short-chain-fatty-acids\|short-chain-fatty-acids]], 담즙산, 트립토판 대사물 |
| **메타단백체(Metaproteomics)** | 단백질 발현 | 실제 기능 활성 확인 |
| **전사체(Transcriptomics)** | RNA 발현 | 유전자 발현 패턴 |
| **숙주 게놈(miGWAS)** | 숙주 유전 변이 | 숙주 유전자-미생물 상관관계 |

### 통계적 고려사항
- 마이크로바이옴 데이터는 **구성적(compositional)** 특성 → 전통적 통계 방법 적용에 제약
- 전문 도구 필요: ALDEx2, ANCOM, DESeq2

## 모델 시스템 기반 기능 분석

서열 데이터만으로는 군집 기능을 예측하기 어려워, **합성 미생물 군집(synthetic community)** 과 **장기 칩(organ-on-a-chip)** 같은 통제 가능한 모델 시스템이 보완적으로 활용된다.

### 합성 미생물 군집 (Synthetic Community)

널리 쓰이는 모델인 Oligo-Mouse-Microbiota(OMM12, 12개 균주) 합성 군집을 대상으로 한 bottom-up 접근에서, 단배양·쌍배양·대사체 분석을 결합해 균주 간 성장·대사 상호작용의 **방향성 네트워크**를 규명하였다 ([[Jay's Knowledge Base/raw/99-weiss-2022-in-vitro-interaction-network-of-a-synthetic-gut-b\|Weiss et al., 2022, *ISME J*]]). 정의된 군집을 사용하면 군집 구성·메타게놈 데이터로부터 기능을 예측하는 원리를 체계적으로 검증할 수 있다.

### 장기 칩(Organ-on-a-Chip) 기반 숙주–미생물 상호작용 모델링

미세유체(microfluidic) 장기 칩은 산소 구배·연동운동·점액층·면역세포를 재현해 숙주 세포와 살아있는 미생물 군집을 장기간 공배양할 수 있는 플랫폼으로, 동물 모델의 종 차이 및 윤리 문제를 우회하면서 숙주–미생물 상호작용을 인과적으로 해부할 수 있게 한다 ([[Jay's Knowledge Base/raw/51-shin-2023-modelling-hostmicrobiome-interactions-in-organ-on\|Shin et al., 2023, *Nat Rev Bioeng*]]). 다중 오믹스·실시간 이미징과 결합 시 in vivo 검증의 중간 단계로 기능한다.

## 시간 차원의 sampling 설계

마이크로바이옴은 일주기·계절·생애주기·식이·항생제·중재 전후로 변동하는 동적 시스템이므로, 분석 설계에서 **시간 차원**을 통제하지 않으면 효과 크기와 재현성이 왜곡된다. Zeng et al. (2026, *The Lancet Microbe*, [[Jay's Knowledge Base/raw/541-zeng-2026-temporal-variations-of-the-gut-microbiome-in-human\|raw/541-zeng-2026-temporal-variations-of-the-gut-microbiome-in-human]])은 인간 장내 마이크로바이옴의 temporal variation을 종합 정리해 다음을 제안한다.

- **단일 시점 → 종단(longitudinal) 설계 전환** — 질병 연관·중재 효능 추정의 통계적 검출력·재현성 향상
- **개인별 baseline variability 보정** — responder 층화(Dao 2016·Mount 2026 [[Jay's Knowledge Base/wiki/obesity-body-composition\|체중 유지 RCT]])의 안정성 확보
- **rate-of-change·resilience 지표** — 항생제 후 회복 궤적, prodromal 단계 진행(Menozzi 2026의 PD 중간 signature)의 dynamic biomarker 화
- **시계열·다중 오믹스 통합 통계** — ALDEx2·ANCOM 등 구성 데이터 도구를 시간 차원으로 확장하는 분석 파이프라인 필요

→ 마이크로바이옴 진단·중재 시험의 표준 설계가 **single-shot에서 longitudinal로** 이동하는 분기점.

## 연구 편향과 분석 범위의 한계

분석 기술의 발전에도 불구하고 문헌 자체에 강한 편향이 존재한다. 서지 분석 결과 **전체 세균학 논문의 절반이 단 10종에 집중**되어 있고, 알려진 세균 종의 약 74%는 연구된 적이 없는 것으로 나타났다 ([[Jay's Knowledge Base/raw/132-jensen-2025-ten-species-comprise-half-of-the-bacteriology-li\|Jensen, 2025]]). 이는 미배양·미연구 분류군을 포착하기 위한 배양 비의존 기법(샷건 메타게노믹스, 단일세포 게노믹스 등)과 합성 군집 모델의 중요성을 강조한다.

## 균수 정량(Enumeration)

포스트바이오틱(비활성 세포) 제품은 생균수(CFU)로 정량할 수 없으므로 **flow cytometry 기반 절대균수** 측정이 표준화되고 있다. 살균 *A. muciniphila* MucT 대상 Arioli (2025) 프로토콜은 동결건조 세포의 재수화 조건·희석액을 최적화해 현미경 계수 대비 낮은 CV(12.3~24.1%)를 달성했고, 6개 실험실 ring test에서 재현성이 검증되어 산업 배치의 mass balance 검증 및 타 포스트바이오틱 원료의 품질 규격에도 이식 가능하다. 공정 연계는 [[Jay's Knowledge Base/wiki/bioprocess-engineering\|bioprocess-engineering]] 참조.

## 출처

- [[Jay's Knowledge Base/raw/05-multi-omics-analysis-methods\|raw/05-multi-omics-analysis-methods]]
- [[Jay's Knowledge Base/raw/488-arioli-2025-quantification-of-pasteurized-akkermansia-muciniphila\|raw/488-arioli-2025-quantification-of-pasteurized-akkermansia-muciniphila]]
- [[Jay's Knowledge Base/raw/31-berg-2020-microbiome-definition-re-visited-old-concepts-and\|raw/31-berg-2020-microbiome-definition-re-visited-old-concepts-and]] — 마이크로바이옴 용어 재정의 및 연구 모범 사례 합의
- [[Jay's Knowledge Base/raw/51-shin-2023-modelling-hostmicrobiome-interactions-in-organ-on\|raw/51-shin-2023-modelling-hostmicrobiome-interactions-in-organ-on]] — 장기 칩 기반 숙주–미생물 상호작용 모델링 리뷰
- [[Jay's Knowledge Base/raw/92-eckburg-2005-diversity-of-the-human-intestinal-microbial-flo\|raw/92-eckburg-2005-diversity-of-the-human-intestinal-microbial-flo]] — 16S rRNA 기반 인간 장내 미생물 다양성·미배양종 발견
- [[Jay's Knowledge Base/raw/99-weiss-2022-in-vitro-interaction-network-of-a-synthetic-gut-b\|raw/99-weiss-2022-in-vitro-interaction-network-of-a-synthetic-gut-b]] — OMM12 합성 군집의 in vitro 상호작용 네트워크
- [[Jay's Knowledge Base/raw/132-jensen-2025-ten-species-comprise-half-of-the-bacteriology-li\|raw/132-jensen-2025-ten-species-comprise-half-of-the-bacteriology-li]] — 10종이 세균학 문헌의 절반 차지, 74% 종 미연구
- [[Jay's Knowledge Base/raw/541-zeng-2026-temporal-variations-of-the-gut-microbiome-in-human\|raw/541-zeng-2026-temporal-variations-of-the-gut-microbiome-in-human]] — 인간 장내 마이크로바이옴의 시간 변동 종설 (*The Lancet Microbe* 2026): 종단 설계·rate-of-change·resilience 지표·시계열 다중오믹스 통합 필요성
