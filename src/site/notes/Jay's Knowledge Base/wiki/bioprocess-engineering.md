---
{"dg-publish":true,"permalink":"/jay-s-knowledge-base/wiki/bioprocess-engineering/","dg-note-properties":{}}
---


# 바이오프로세스 공학

## 개요

바이오프로세스 공학(Bioprocess Engineering)은 미생물 기반 제품의 대량 생산을 위한 배양(fermentation), 정제(downstream processing), 제형화(formulation) 기술을 포괄하는 분야이다. 차세대 프로바이오틱스(NGP) 및 LBP 개발에서는 절대혐기성(strict anaerobe) 균주의 고농도 배양(high-cell-density culture), 효율적인 바이오매스 회수, 생균 안정성 확보가 핵심 공정 과제이다.

*Akkermansia muciniphila*의 경우, 전통적인 정치배양(static culture) 대비 in vitro bionic intestinal reactor를 활용한 동적배양(dynamic culture)에서 바이오매스가 44.36% 향상되었으며(BPM 배지 기준 1.92 g/L 달성), 뮤신 함유 배지에서의 성장 대사 및 형태 변화가 상세히 규명되었다 (Li 2021). 뮤신 고갈 조건에서는 뮤신 분해 효소 유전자의 발현이 상향 조절되고, 세포외 소포(extracellular vesicles) 생산이 증가하는 등 프로바이오틱 특성이 변화한다 (Shin 2019). 산업 생산용으로는 동물유래 성분이 없는 food-grade 배지가 요구되며, 게놈 스케일 대사 모델 기반 defined minimal medium 설계(GlcNAc 필수성 규명, Ark 2018), 식물성 배지에서의 오믹스 검증(Geerlings 2024), 고밀도 배양(HCD) 전략(Wu 2023)이 차례로 보고되었다.

고농도 배양 공정(HCD process)의 clarification(정제 전 고형분 제거) 단계에서는 기존 fed-batch 공정(< 100 g/L WCW) 대비 100 million cells/mL 이상의 초고밀도 조건에서 바이오매스 로딩 용량과 제품 회수율의 한계가 발생한다. 유동층 원심분리기(fluidized bed centrifuge)와 같은 단회용(single-use) 기술이 대안으로 제시되고 있으며 (Saballus 2021), 관형 보울 원심분리기(tubular bowl centrifuge)는 미세 입자 및 생물학적 세포의 고효율 분리에 적합한 것으로 평가된다 (Spelter 2010). 이러한 분리 공정 기술은 NGP 균주의 산업적 스케일업에 직접 적용 가능하다.

## 주요 내용/기전

- **In vitro 장내 반응기**: bionic intestinal reactor를 이용한 *A. muciniphila* 동적 배양으로 바이오매스 44.36% 향상. BHI, BPM(BHI + porcine mucin) 등 5종 배지 비교 평가. 동적 배양 조건이 균주의 성장, 대사산물(SCFA 포함), 형태에 미치는 영향 분석 (Li 2021)
- **뮤신 고갈 반응**: *A. muciniphila*에서 뮤신 고갈 시 뮤신 분해 효소 유전자 발현 상향 조절, 세포외 단백질 발현 변화, 장 항상성(intestinal homeostasis) 및 장벽 완전성 조절 기전 규명. 전사체(transcriptome) 분석 기반 (Shin 2019)
- **고농도 배양 정제(HCD clarification)**: 100 million cells/mL 수준의 초고밀도 단클론 항체 공정에서 단회용 유동층 원심분리기(single-use fluidized bed centrifuge) 적용. 기존 기술 대비 높은 바이오매스 로딩 용량과 제품 회수율 확보 (Saballus 2021)
- **관형 보울 원심분리**: 미세 입자 및 생물학적 세포 분리를 위한 관형 보울 원심분리기의 고원심력(high centrifugal force) 활용. 나노스케일 소재 분리 및 반연속(semibatch) 운전 최적화 (Spelter 2010)
- **유세포 분석(Flow cytometry) 기반 균수 측정**: 프로바이오틱스 및 포스트바이오틱스의 분석법으로 유세포 분석 활용, 전통적 CFU 측정법 대비 신속하고 비용 효율적인 균수 열거(enumeration) 워크플로우 제시 (Boyte 2023, Bolzon 2024)
- **살균 *A. muciniphila* MucT 절대균수 정량 프로토콜**: 고밀도·표준화 산업 배치 대상으로 flow cytometry 기반 절대균수(absolute counting) 프로토콜 최적화. 동결건조 세포의 재수화 조건 및 희석액 선택으로 세포 응집(aggregate) 최소화 → 현미경 계수 대비 낮은 CV 달성. 고밀도 배치에서 목표 세포 용량의 표준화 배치까지 이어지는 생산 공정 전반에 대한 **mass balance 검증**에 적용. 6개 독립 실험실 ring test 결과: 평균 CV 12.3~24.1%, 최대 Z-score 2.64 → 다른 포스트바이오틱에도 이식 가능한 신속·재현성·정확성 있는 정량법으로 평가 (Arioli 2025)
- **장기 배양 시 게놈 안정성**: *A. muciniphila* MucT(ATCC BAA-835 / DSM 22959) 표준 균주가 장기 배양(long-term culturing) 조건에서도 게놈 안정성을 유지함이 확인됨. NGP 산업 스케일업의 핵심 우려인 **계대 배양 누적에 따른 유전자형 표류(drift)** 가능성에 대한 안전 근거로, MCB/WCB 일관성과 release specification 설정에 직접 적용 (Ligthart 2026, *Microbiology Spectrum*)
- **defined minimal medium 모델 설계**: *A. muciniphila* 게놈 스케일 대사 모델과 mucin 조성으로부터 합성 최소배지를 설계. GlmS 부재 → Fru6P에서 GlcN6P를 형성하지 못해 **N-acetylglucosamine(GlcNAc) 첨가가 성장에 필수**임을 규명, 갱신된 모델로 합성배지 성장 예측 정확도 확보. 산업 배지 처방·배지 비용 최적화·재현성 있는 release의 분자적 기반 (Ark 2018, *Microbial Biotechnology*) → 상세 [[Jay's Knowledge Base/wiki/akkermansia-muciniphila\|akkermansia-muciniphila]]
- **food-grade 식물성 배지 + 오믹스 검증**: 동물유래·알레르겐 없는 식물 기반 배지에서 GlcNAc:glucose 비율을 달리한 배치 반응기 배양. mucin 배지 대비 OD600·세포 신장 증가, 전사체·프로테옴상 glycosyltransferase·신호·스트레스 반응 차이는 있으나 성장 저해 없음 → **치료용 고수율 생산을 위한 animal-free 배지 플랫폼 실증** (Geerlings 2024, *Microbiome Research Reports*)
- **고밀도 배양(HCD) 전략**: *A. muciniphila* 고세포밀도 배양 전략과 잠재 대사 경로 분석 → 비용 효율적 산업 생산 플랫폼 설계의 핵심 (Wu 2023, *Microbiology Spectrum*)
- **프로바이오틱 균주의 산업/장내 스트레스 하 게놈 무결성**: *L. rhamnosus* GG를 ~1,000세대 실험적 진화시킨 결과, 무스트레스·염 스트레스에서는 안정적이나 **담즙·반복 전단(shear) 스트레스에서 IS element 활성화로 mucus-binding SpaCBA pilus 유전자 클러스터가 결실**되고 DNA polymerase 변이 mutator 계통도 출현. 산업 제조(ex vivo)·장관(in vivo) 스트레스가 프로바이오틱 기능 표현형의 안정성을 좌우함을 입증 → 균주 stability 평가·공정 스트레스 설계의 일반 원리 (Douillard 2016, *Applied and Environmental Microbiology*; cf. Ligthart 2026의 *A. muciniphila* 게놈 안정성과 대비)
- **스트레스 priming을 통한 균주 강건성(robustness) 확보**: 가벼운 사전 스트레스(stress priming)에 미생물을 노출시키면 이후의 강한 스트레스(triggering)에 대한 생존율이 향상된다. 34개 연구·250+ 시험의 메타분석 결과, priming된 미생물의 생존율은 비-priming 대비 **약 10배 높았으며**, 효과 크기는 미생물 분류군·스트레스 유형 등 조절변수에 의존 ([[Jay's Knowledge Base/raw/84-andradelinares-2016-microbial-stress-priming-a-metaanalysis\|Andrade-Linares 2016, *Environ. Microbiol.*]]). 신경계 없는 생물(세균·진균·식물)에서도 스트레스 자극의 경험·기억으로 표현형을 미리 대비시키는 priming 개념틀이 정립되어 있어 ([[Jay's Knowledge Base/raw/85-hilker-2016-priming-and-memory-of-stress-responses-in-organi\|Hilker 2016, *Biol. Rev.*]]), 발효·동결건조·위장관 통과 등 공정·생체 스트레스에 대한 프로바이오틱/LBP 균주의 내성을 사전 적응으로 강화하는 전략의 일반 원리를 제공한다. 단, 반복적 강(强)스트레스는 게놈 무결성 손실(상기 Douillard 2016)을 유발할 수 있어 priming 강도·횟수의 공정 설계 최적화가 필요하다. 균주별 사전 적응 적용 사례는 [[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]] 참조
- **산소 민감성 극복**: 절대혐기성 NGP 균주의 산업적 생산에서 산소 노출 최소화를 위한 공정 설계, 혐기 챔버(anaerobic chamber) 기반 배양 및 제형화 전략
- **알지네이트 마이크로캡슐화로 산소 내성·저장 안정성 확보 (Quah 2026)**: *A. muciniphila*는 호기 노출이 지속되면 생존율이 검출한계 이하로 급감하나, **sodium alginate + resistant starch 압출(extrusion) 마이크로캡슐화**로 자유세포(free cell) 대비 저장 중 안정성·생존율이 유의하게 향상됐다. 비영양 환경에서 저온이 생존에 유리, sodium citrate 농도는 비드 용해에는 영향하나 생존 세포 수에는 무영향 → **산소 민감성 NGP의 안정적 경구 전달 시스템** 설계 근거. 대장암(CRC) 중재 응용을 겨냥 ([[Jay's Knowledge Base/raw/534-quah-2026-microencapsulation-strategy-for-aerobic-cultivation-of\|raw/534-quah-2026-microencapsulation-strategy-for-aerobic-cultivation-of]]; cf. [[Jay's Knowledge Base/wiki/microbiome-cancer-immunotherapy\|microbiome-cancer-immunotherapy]])
- **스케일업 고려사항**: 실험실 규모에서 산업 규모로의 전환 시 배양 조건 일관성, 배지 원료 관리, 무균 조작(aseptic processing), GMP 준수 등이 핵심 과제

## 관련 raw/ 소스

- [[Jay's Knowledge Base/raw/84-andradelinares-2016-microbial-stress-priming-a-metaanalysis\|raw/84-andradelinares-2016-microbial-stress-priming-a-metaanalysis]] — 스트레스 priming의 미생물 생존율 ~10배 향상 메타분석
- [[Jay's Knowledge Base/raw/85-hilker-2016-priming-and-memory-of-stress-responses-in-organi\|raw/85-hilker-2016-priming-and-memory-of-stress-responses-in-organi]] — 신경계 없는 생물의 스트레스 priming·기억 개념틀
- [[Jay's Knowledge Base/raw/100-saballus-2021-a-novel-clarification-approach-for-intensified\|raw/100-saballus-2021-a-novel-clarification-approach-for-intensified]]
- [[Jay's Knowledge Base/raw/101-spelter-2010-processing-of-dispersions-containing-fine-parti\|raw/101-spelter-2010-processing-of-dispersions-containing-fine-parti]]
- [[Jay's Knowledge Base/raw/241-li-2021-study-of-growth-metabolism-and-morphology-of-akkerma\|raw/241-li-2021-study-of-growth-metabolism-and-morphology-of-akkerma]]
- [[Jay's Knowledge Base/raw/242-shin-2019-elucidation-of-akkermansia-muciniphila-probiotic-t\|raw/242-shin-2019-elucidation-of-akkermansia-muciniphila-probiotic-t]]
- [[Jay's Knowledge Base/raw/244-shin-2019-elucidation-of-akkermansia-muciniphila-probiotic-t\|raw/244-shin-2019-elucidation-of-akkermansia-muciniphila-probiotic-t]]
- [[Jay's Knowledge Base/raw/290-boyte-2023-probiotic-and-postbiotic-analytical-methods-a-per\|raw/290-boyte-2023-probiotic-and-postbiotic-analytical-methods-a-per]]
- [[Jay's Knowledge Base/raw/291-bolzon-2024-a-streamlined-workflow-for-a-fast-and-cost-effec\|raw/291-bolzon-2024-a-streamlined-workflow-for-a-fast-and-cost-effec]]
- [[Jay's Knowledge Base/raw/488-arioli-2025-quantification-of-pasteurized-akkermansia-muciniphila\|raw/488-arioli-2025-quantification-of-pasteurized-akkermansia-muciniphila]]
- [[Jay's Knowledge Base/raw/506-ligthart-2026-high-stability-of-the-genome-of-akkermansia\|raw/506-ligthart-2026-high-stability-of-the-genome-of-akkermansia]]
- [[Jay's Knowledge Base/raw/522-douillard-2016-polymorphisms-chromosomal-rearrangements-and-mutator\|raw/522-douillard-2016-polymorphisms-chromosomal-rearrangements-and-mutator]]
- [[Jay's Knowledge Base/raw/523-geerlings-2024-omics-based-analysis-of-akkermansia-muciniphila\|raw/523-geerlings-2024-omics-based-analysis-of-akkermansia-muciniphila]]
- [[Jay's Knowledge Base/raw/525-ark-2018-modeldriven-design-of-a-minimal-medium-for-akkermansia\|raw/525-ark-2018-modeldriven-design-of-a-minimal-medium-for-akkermansia]]
- [[Jay's Knowledge Base/raw/526-wu-2023-strategies-for-high-cell-density-cultivation-of\|raw/526-wu-2023-strategies-for-high-cell-density-cultivation-of]]
- [[Jay's Knowledge Base/raw/534-quah-2026-microencapsulation-strategy-for-aerobic-cultivation-of\|raw/534-quah-2026-microencapsulation-strategy-for-aerobic-cultivation-of]] — 알지네이트(+resistant starch) 마이크로캡슐화로 산소 민감 *A. muciniphila*의 호기 생존·저장 안정성 향상, CRC 전달 시스템 응용

## 관련 wiki 링크

- [[Jay's Knowledge Base/wiki/next-generation-probiotics\|next-generation-probiotics]]
- [[Jay's Knowledge Base/wiki/akkermansia-muciniphila\|akkermansia-muciniphila]]
- [[Jay's Knowledge Base/wiki/lbp-regulatory-cmc\|lbp-regulatory-cmc]]
- [[Jay's Knowledge Base/wiki/short-chain-fatty-acids\|short-chain-fatty-acids]]
- [[Jay's Knowledge Base/wiki/microbiome-therapeutics\|microbiome-therapeutics]]
- [[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]]
