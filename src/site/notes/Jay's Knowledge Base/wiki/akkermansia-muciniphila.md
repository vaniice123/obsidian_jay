---
{"dg-publish":true,"permalink":"/jay-s-knowledge-base/wiki/akkermansia-muciniphila/","dg-note-properties":{}}
---

# Akkermansia muciniphila

*Akkermansia muciniphila*는 장 점막층(mucin layer)에 서식하는 그람음성 혐기성 세균으로, 건강한 성인 장내 미생물의 **1~4%**를 차지하며 장 장벽 기능, 대사 조절, 면역 항상성에 핵심적 역할을 한다. 살균(pasteurized) 형태의 포스트바이오틱이 살아있는 균주와 동등하거나 더 우수한 효능을 보이는 것이 2019년 proof-of-concept RCT에서 확인되었고, **2026년 *Nature Medicine* RCT(n=90)에서 체중 감량 후 유지(weight-loss maintenance)에서 위약 대비 체중 재증가 억제 효과가 확인**되었으며, 현재 NGP(Next Generation Probiotics) 및 GLP-1 companion 서플리먼트로서 상업적·임상적 가치가 급부상하고 있다.

> 📑 이 주제는 분량이 커 **허브 + 5개 세부(spoke) 문서**로 구성된다. 본 허브 문서는 정의·분류학·핵심 활성 성분(Amuc_1100)·작용 기전 요약과 **전체 출처(master bibliography)**를 유지하며, 세부 내용은 아래 [세부 주제 문서](#세부-주제-문서-spokes)로 분리되어 있다.

---

## 발견과 분류학 (Discovery & Taxonomy)

*A. muciniphila*는 인간 분변을 위 점액(gastric mucin) 단일 탄소·질소원 혐기 배지에서 dilution-to-extinction 배양해 분리한 우점 점액 분해균 **MucT 균주**로 2004년 최초 기재되었다 ([[Jay's Knowledge Base/raw/521-derrien-2004-akkermansia-muciniphila-gen-nov-sp-nov-a-human\|Derrien et al., 2004, *Int. J. Syst. Evol. Microbiol.*]]). 그람음성·절대혐기·비운동성·비포자 형성 난형균으로, 16S rRNA 분석상 **Verrucomicrobia 문(phylum)** 1아분류군에 속하는 신규 속·종 *Akkermansia muciniphila* gen. nov., sp. nov.가 제안되었다. 표준 균주 MucT는 **ATCC BAA-835T = CIP 107961T(= DSM 22959)**로 기탁되어 이후 모든 *A. muciniphila* 연구·산업 균주의 reference가 된다.

- 점액을 주 탄소·질소원으로 이용 (DNA G+C 47.6 mol%)
- N-acetylglucosamine(GlcNAc)·N-acetylgalactosamine·glucose 등 제한된 당만 이용 가능하며, 단백질원이 있을 때만 성장 (mucin 대비 성장 속도·최종 밀도 낮음) → **점막 niche 적응**의 생리적 기반 (cf. [[Jay's Knowledge Base/wiki/bioprocess-engineering\|배지 설계]])
- 16S rRNA 서열이 미배양 대장 세균 3종과 99% 유사 → 인간 장내 우점 공생균임을 시사

> *Akkermansia* 속의 종 분화("beyond muciniphila", *A. massiliensis* sp. nov. 등)와 균주 다양성·게놈 안정성·배양 생리는 → [[Jay's Knowledge Base/wiki/akkermansia-strain-landscape\|akkermansia-strain-landscape]] 참조.

---

## 핵심 활성 성분: Amuc_1100

- *A. muciniphila*의 가장 풍부한 외막 단백질(outer membrane protein)
- 녹는점 70°C → **살균(pasteurization) 후에도 구조·기능 보존**
- **TLR2 신호 활성화** → 장 장벽 강화, 염증 조절
- **PI3K/Akt 경로 활성화** → 인슐린 감수성, 근단백 합성 촉진
- **전임상 기원 (Plovier et al., 2017, *Nature Medicine*, [[Jay's Knowledge Base/raw/524-plovier-2017-a-purified-membrane-protein-from-akkermansia\|raw/524-plovier-2017-a-purified-membrane-protein-from-akkermansia]])**: 정제 Amuc_1100 단독 또는 **살균(pasteurized) 균체**가 비만·당뇨 마우스에서 대사를 개선하며, 특히 *A. muciniphila*의 **살균이 생균 대비 대사 개선 효과를 오히려 증대**시킴을 입증 — 「살균 ≥ 생균」 패러다임과 Amuc_1100 활성 성분 가설의 foundational 근거
- 2019 Depommier RCT: 살균 *A. muciniphila*가 생균과 **동등 이상**의 인슐린 감수성 개선 (Plovier 2017 전임상 → 인체 proof-of-concept으로 연결)

### 별도 분비 단백질: GLP-1 유도 인자 (Yoon 2021)

Amuc_1100과 별개로, *A. muciniphila*는 **L-cell 유래 GLP-1 분비를 유도하는 분비 단백질**을 생산함이 분리·동정됨 (Yoon et al., 2021, *Nature Microbiology*, [[Jay's Knowledge Base/raw/513-yoon-2021-akkermansia-muciniphila-secretes-a-glucagon-like\|raw/513-yoon-2021-akkermansia-muciniphila-secretes-a-glucagon-like]]). 이 단백질의 보충은 마우스 대사질환 모델에서 포도당 항상성을 개선했으며, 살균 *A. muciniphila* 또는 그 생균 보충 시 **혈중 GLP-1 농도 상승**이 관찰되는 일관된 메커니즘적 근거로 작용. GLP-1RA가 호르몬 모방약(외인성)인 반면, Akkermansia 유래 인자는 **장 내인성(endogenous) GLP-1 분비 자극**이라는 점에서 [[Jay's Knowledge Base/wiki/glp1-muscle-loss\|GLP-1 companion]] 포지셔닝의 차별 기전이며, Gao 2026의 "병용 시 혈중 GLP-1 추가 증가" 관찰을 뒷받침하는 foundational mechanism.

> Amuc_1409·AmTARS·세포외소포(EV)·GABA·CAZyme 등 추가 분비 effector와 4대 작용 기전(장벽·대사·근육·면역)의 상세는 → [[Jay's Knowledge Base/wiki/akkermansia-mechanisms\|akkermansia-mechanisms]] 참조.

---

## 작용 기전 (요약)

상세는 [[Jay's Knowledge Base/wiki/akkermansia-mechanisms\|akkermansia-mechanisms]] 문서로 분리. 핵심 4대 축은:

1. **장 장벽 강화** — 점막층 두께·tight junction(ZO-1, occludin)↑, LPS 전위 감소 → 전신 염증 억제 ([[Jay's Knowledge Base/wiki/dysbiosis\|dysbiosis]] 시 leaky gut 핵심)
2. **대사 조절** — 인슐린 감수성·체지방·혈당 개선, [[Jay's Knowledge Base/wiki/short-chain-fatty-acids\|short-chain-fatty-acids]] 생태 지원, 운동 유도 대사 개선의 매개자. 전임상 토대: Everard 2013·Dao 2016·살균형 기전 연구
3. **근육 건강 (장-근육 축)** — Follistatin↑(myostatin 격리)·EV의 근단백 합성 자극·근위축 모델 근보호 ([[Jay's Knowledge Base/wiki/gut-muscle-axis\|gut-muscle-axis]])
4. **면역 조절** — TLR2 항염·Treg 분화·분비형 AmTARS의 M2 대식세포 분극·[[Jay's Knowledge Base/wiki/faecalibacterium-prausnitzii\|faecalibacterium-prausnitzii]]와의 면역질환 시너지

> GLP-1RA 병용 대사 시너지에 대한 비판적 검토는 → [[Jay's Knowledge Base/wiki/akkermansia-clinical-evidence\|akkermansia-clinical-evidence]] 참조.

---

## 세부 주제 문서 (Spokes)

| 문서 | 다루는 범위 |
|------|-------------|
| [[Jay's Knowledge Base/wiki/akkermansia-mechanisms\|akkermansia-mechanisms]] | 추가 분비 effector(Amuc_1409·AmTARS·EV·GABA·CAZyme), 4대 작용 기전 상세 |
| [[Jay's Knowledge Base/wiki/akkermansia-clinical-evidence\|akkermansia-clinical-evidence]] | 살균 포스트바이오틱 인체 RCT·장외 임상, GLP-1RA 시너지 비판적 검토, GLP-1 companion 포지셔닝·ActRII 접점 |
| [[Jay's Knowledge Base/wiki/akkermansia-indications-applications\|akkermansia-indications-applications]] | IBD/UC·적응증별 전임상 효능, living co-therapy 약물 캐리어, engineered NGP, 점액분해·pathobiont 양면성 |
| [[Jay's Knowledge Base/wiki/akkermansia-strain-landscape\|akkermansia-strain-landscape]] | 종 분화(*A. massiliensis* 등), MucT 게놈 안정성, food-grade 배양·대사 생리, 분리주 다양성·안전성·역가 |
| [[Jay's Knowledge Base/wiki/akkermansia-commercialization\|akkermansia-commercialization]] | 주요 기업·제품, EFSA novel food 규제(2021/2025), 서지 계량 지형, 글로벌 시장 |

---

## 관련 문서

- [[Jay's Knowledge Base/wiki/glp1-muscle-loss\|glp1-muscle-loss]] — GLP-1 근손실과 ActRII 경쟁 환경
- [[Jay's Knowledge Base/wiki/gut-muscle-axis\|gut-muscle-axis]] — 장-근육 축 기전 상세
- [[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]] — 바이오틱스 분류와 포스트바이오틱 장점
- [[Jay's Knowledge Base/wiki/short-chain-fatty-acids\|short-chain-fatty-acids]] — SCFA의 근육 건강 기전
- [[Jay's Knowledge Base/wiki/microbiome-therapeutics\|microbiome-therapeutics]] — 마이크로바이옴 치료제 개발 동향

## 출처

> 본 절은 *A. muciniphila* 주제 전체(허브 + 5개 spoke)의 **통합 서지(master bibliography)**이다. 각 spoke 문서는 본문에 inline 인용을 유지하며, 전체 annotated 목록은 여기에서 단일 관리한다.

- [[Jay's Knowledge Base/raw/12-bimagrumab-believe-phase2b-glp1-muscle-preservation\|raw/12-bimagrumab-believe-phase2b-glp1-muscle-preservation]]
- [[Jay's Knowledge Base/raw/13-hb05p-actrii-pathway-literature-survey-and-market\|raw/13-hb05p-actrii-pathway-literature-survey-and-market]]
- [[Jay's Knowledge Base/raw/14-hb05p-glp1-companion-strategic-positioning\|raw/14-hb05p-glp1-companion-strategic-positioning]]
- [[Jay's Knowledge Base/raw/442-perraudeau-2020-improvements-to-postprandial-glucose-control-in-su\|raw/442-perraudeau-2020-improvements-to-postprandial-glucose-control-in-su]] — WBF-011 다균주 프로바이오틱(A. muciniphila 포함) T2D RCT
- [[Jay's Knowledge Base/raw/488-arioli-2025-quantification-of-pasteurized-akkermansia-muciniphila\|raw/488-arioli-2025-quantification-of-pasteurized-akkermansia-muciniphila]] — 살균 *A. muciniphila* MucT의 flow cytometry 정량 프로토콜 및 6개 실험실 ring test (CV 12.3~24.1%)
- [[Jay's Knowledge Base/raw/490-chmurska-2026-relationship-between-akkermansia-muciniphila-abundance\|raw/490-chmurska-2026-relationship-between-akkermansia-muciniphila-abundance]] — 운동-유도 체지방 감소에서 *A. muciniphila*의 매개자 역할, 기전(장벽·면역·SCFA·AMPK)
- [[Jay's Knowledge Base/raw/491-gao-2026-combination-of-glp-1-receptor-agonist-and-akkermansia\|raw/491-gao-2026-combination-of-glp-1-receptor-agonist-and-akkermansia]] — Akk11 + semaglutide 병용 db/db T2D/MASLD 마우스 대사 개선 (체지방·간지질·LPS·내인성 GLP-1↑). 단, **lean mass는 추가 감소**·체성분 도구(TD-NMR) 한계로 근손실 보존 주장 미입증, "synergy" 통계 검증 부재 — 비판적 검토 필요
- [[Jay's Knowledge Base/raw/507-lee-2026-critical-reading-of-akk-glp1-paper\|raw/507-lee-2026-critical-reading-of-akk-glp1-paper]] — Gao 2026에 대한 비판적 재검토 에세이 (체성분 도구의 함정, lean mass 해석 한계, 4군 설계 결여, "synergy" 통계 부재, CFU/사균 표기 모순 등 방법론 이슈 정리)
- [[Jay's Knowledge Base/raw/493-kurt-cakmaktas-2026-comparative-cytotoxicity-and-molecular-profiling-of\|raw/493-kurt-cakmaktas-2026-comparative-cytotoxicity-and-molecular-profiling-of]] — 3종 *A. muciniphila* 균주 유래 포스트바이오틱의 위암(AGS)·대장암(HCT116) 세포 비교 세포독성, LC-QTOF-MS/¹H NMR 프로파일링
- [[Jay's Knowledge Base/raw/506-ligthart-2026-high-stability-of-the-genome-of-akkermansia\|raw/506-ligthart-2026-high-stability-of-the-genome-of-akkermansia]] — *A. muciniphila* MucT 표준 균주의 장기 배양 조건 하 게놈 안정성 (*Microbiology Spectrum* 2026, MCB/CMC 근거)
- [[Jay's Knowledge Base/raw/508-efsa-panel-on-nutrition,-novel-foods-and-food-allergens-(nda)-2025-safety-of-an-extension-of-use-of-pasteurised\|raw/508-efsa-panel-on-nutrition,-novel-foods-and-food-allergens-(nda)-2025-safety-of-an-extension-of-use-of-pasteurised]] — EFSA NDA Panel 2025, 살균 *A. muciniphila* novel food 사용 확장(12세 이상 청소년) 안전성 평가 (*EFSA Journal*)
- [[Jay's Knowledge Base/raw/509-feng-2025-investigating-the-role-of-akkermansia-muciniphila\|raw/509-feng-2025-investigating-the-role-of-akkermansia-muciniphila]] — 영아 분리주 Akk11 (생균/살균) HFD 비만 마우스 보호 효과, 균주별 SCFA 프로파일 (*Front. Microbiol.*)
- [[Jay's Knowledge Base/raw/510-hamaguchi-2026-bacterial-constipation-mucin-degrading-intestinal\|raw/510-hamaguchi-2026-bacterial-constipation-mucin-degrading-intestinal]] — 점액 분해성 공생균과 변비 가설 (*Gut Microbes* 2026, 모니터링 대상)
- [[Jay's Knowledge Base/raw/511-han-2025-pasteurized-akkermansia-muciniphila-timepie001\|raw/511-han-2025-pasteurized-akkermansia-muciniphila-timepie001]] — 살균 *A. muciniphila* Timepie001+의 DSS-UC 보호 (살균 > 생균) (*Front. Microbiol.*)
- [[Jay's Knowledge Base/raw/512-wang-2025-bibliometric-analysis-of-research-trends-and\|raw/512-wang-2025-bibliometric-analysis-of-research-trends-and]] — *A. muciniphila* 서지 계량 분석 2010-2024 (*Front. Microbiol.*, 4,423편)
- [[Jay's Knowledge Base/raw/513-yoon-2021-akkermansia-muciniphila-secretes-a-glucagon-like\|raw/513-yoon-2021-akkermansia-muciniphila-secretes-a-glucagon-like]] — *A. muciniphila* 분비 GLP-1 유도 단백질 동정, 마우스 대사 개선 (*Nature Microbiology* 2021, foundational mechanism)
- [[Jay's Knowledge Base/raw/514-zhang-2025-the-worldview-of-akkermansia-muciniphila-a\|raw/514-zhang-2025-the-worldview-of-akkermansia-muciniphila-a]] — *A. muciniphila* 학술·특허 진화 분석 (*Front. Microbiol.*, NAFLD·암 면역·신경퇴행 신흥 응용)
- [[Jay's Knowledge Base/raw/515-ma-2026-delivery-system-based-on-akkermansia-muciniphila\|raw/515-ma-2026-delivery-system-based-on-akkermansia-muciniphila]] — SAL@AKK@EL100, 살리드로사이드 적재 살아있는 *A. muciniphila* + Eudragit L100 장용 코팅, Dex 유도 골다공증 zebrafish 모델 (*Adv. Healthc. Mater.* 2026, 경구 living co-therapy 플랫폼)
- [[Jay's Knowledge Base/raw/517-ouwerkerk-2022-comparative-genomics-and-physiology-of-akkermansia\|raw/517-ouwerkerk-2022-comparative-genomics-and-physiology-of-akkermansia]] — 6개 신규 인간 분리주의 비교유전체·프로테옴·생리학 분석, **Amuc1/AmucU 아종 분기** + 단일 보유자의 다중 균주 보유 + mucin 분해 보존 + AMR 안전성 (*Microorganisms* 2022)
- [[Jay's Knowledge Base/raw/518-mount-2026-pasteurized-akkermansia-muciniphila-muct-for-weight\|raw/518-mount-2026-pasteurized-akkermansia-muciniphila-muct-for-weight]] — 살균 *A. muciniphila* MucT 체중 감량 유지 RCT (과체중·비만 성인 n=90, 24주). 체중 재증가 억제(1.2 vs 3.2 kg, P=0.012)·순 체중 감량 3.1 kg 더 큼(P=0.009)·초기 *Akkermansia* 풍부도와 심대사 반응 연관·중대 이상반응 없음 (*Nature Medicine* 2026, NCT05417360)
- [[Jay's Knowledge Base/raw/521-derrien-2004-akkermansia-muciniphila-gen-nov-sp-nov-a-human\|raw/521-derrien-2004-akkermansia-muciniphila-gen-nov-sp-nov-a-human]] — *A. muciniphila* gen. nov., sp. nov. 최초 분리·기재. MucT 표준 균주(ATCC BAA-835T), Verrucomicrobia, mucin 단일 C/N원 (*Int. J. Syst. Evol. Microbiol.* 2004, **foundational taxonomy**)
- [[Jay's Knowledge Base/raw/523-geerlings-2024-omics-based-analysis-of-akkermansia-muciniphila\|raw/523-geerlings-2024-omics-based-analysis-of-akkermansia-muciniphila]] — food-grade 식물성 배지에서의 *A. muciniphila* 배양·오믹스 분석, animal-free 산업 생산 배지 가능성 (*Microbiome Res. Rep.* 2024)
- [[Jay's Knowledge Base/raw/524-plovier-2017-a-purified-membrane-protein-from-akkermansia\|raw/524-plovier-2017-a-purified-membrane-protein-from-akkermansia]] — 정제 Amuc_1100·살균 균체의 비만/당뇨 마우스 대사 개선, 살균이 효과 증대 (*Nature Medicine* 2017, **Amuc_1100·살균 패러다임 전임상 기원**)
- [[Jay's Knowledge Base/raw/525-ark-2018-modeldriven-design-of-a-minimal-medium-for-akkermansia\|raw/525-ark-2018-modeldriven-design-of-a-minimal-medium-for-akkermansia]] — 게놈 스케일 모델 기반 defined minimal medium 설계, GlcNAc 필수성·mucus 적응 확인 (*Microb. Biotechnol.* 2018)
- [[Jay's Knowledge Base/raw/526-wu-2023-strategies-for-high-cell-density-cultivation-of\|raw/526-wu-2023-strategies-for-high-cell-density-cultivation-of]] — *A. muciniphila* 고밀도 배양(HCD) 전략 및 잠재 대사 경로 (*Microbiol. Spectr.* 2023)
- [[Jay's Knowledge Base/raw/23-kim-2023-secreted-akkermansia-muciniphila-threonyl-trna-synt\|raw/23-kim-2023-secreted-akkermansia-muciniphila-threonyl-trna-synt]] — 분비형 AmTARS(threonyl-tRNA synthetase)가 M2 대식세포 분극·항염 사이토카인 유도로 면역 항상성 감시·조절 (*Cell Host & Microbe* 2023)
- [[Jay's Knowledge Base/raw/26-wosinska-2023-akkermansia-muciniphila-multifunctional-bacter\|raw/26-wosinska-2023-akkermansia-muciniphila-multifunctional-bacter]] — *A. muciniphila* 다기능성 종설(발견·다양성·질환 연관 개요) (*J. Educ. Health Sport* 2023)
- [[Jay's Knowledge Base/raw/30-abot-2023-pasteurized-akkermansia-muciniphila-improves-gluco\|raw/30-abot-2023-pasteurized-akkermansia-muciniphila-improves-gluco]] — 살균 *A. muciniphila*가 시상하부 NO 방출 증가를 동반한 장-뇌 축 경유로 혈당 개선 (고지방식 마우스, *Heliyon* 2023)
- [[Jay's Knowledge Base/raw/34-li-2023-iakkermansia-muciniphilai-supplementation-prevents-c\|raw/34-li-2023-iakkermansia-muciniphilai-supplementation-prevents-c]] — 수면박탈 마우스에서 미세아교세포 시냅스 탐식 조절을 통한 인지장애 예방 (*Gut Microbes* 2023)
- [[Jay's Knowledge Base/raw/53-lee-2023-iakkermansia-muciniphilai-promotes-testosteronemedi\|raw/53-lee-2023-iakkermansia-muciniphilai-promotes-testosteronemedi]] — 생균·살균 경구 투여가 테스토스테론 매개 모발 성장 억제 완화 (마우스, *FASEB BioAdvances* 2023)
- [[Jay's Knowledge Base/raw/55-he-2023-iakkermansia-muciniphilai-protects-the-intestine-fro\|raw/55-he-2023-iakkermansia-muciniphilai-protects-the-intestine-fro]] — *A. muciniphila*가 프로피온산 분비로 방사선 유도 장손상·염증 완화 (*Gut Microbes* 2023; 266과 동일 논문)
- [[Jay's Knowledge Base/raw/57-konstanti-2023-physiology-of-γ-aminobutyric-acid-production\|raw/57-konstanti-2023-physiology-of-γ-aminobutyric-acid-production]] — *A. muciniphila*의 GABA 생산 생리(GAD·산성 스트레스 적응) (*Appl. Environ. Microbiol.* 2023, 장-뇌 축 대사산물 근거)
- [[Jay's Knowledge Base/raw/74-everard-2013-cross-talk-between-iakkermansia-muciniphilai-an\|raw/74-everard-2013-cross-talk-between-iakkermansia-muciniphilai-an]] — *A. muciniphila*–장상피 cross-talk이 식이유도 비만·인슐린 저항성·장벽을 제어 (*PNAS* 2013, **기념비적 대사 전임상**)
- [[Jay's Knowledge Base/raw/81-teng-pasteurized-akkermansia-muciniphila-improves-immunity-a\|raw/81-teng-pasteurized-akkermansia-muciniphila-improves-immunity-a]] — 살균 *A. muciniphila*가 5-FU 처리 BALB/c 마우스에서 면역 회복·독성 경감 (Teng)
- [[Jay's Knowledge Base/raw/86-kang-2024-the-secreted-protein-amuc-1409-from-akkermansia-mu\|raw/86-kang-2024-the-secreted-protein-amuc-1409-from-akkermansia-mu]] — 분비 단백질 Amuc_1409가 Lgr5⁺ 장줄기세포 조절로 장 건강 개선 (*Nature Communications* 2024; 273과 동일 논문)
- [[Jay's Knowledge Base/raw/104-hou-2023-safety-evaluation-and-probiotic-potency-screening-o\|raw/104-hou-2023-safety-evaluation-and-probiotic-potency-screening-o]] — 분변·모유 유래 31개 *A. muciniphila* 분리주의 안전성·프로바이오틱 역가 스크리닝(AM01~06) (*Microbiol. Spectr.* 2023)
- [[Jay's Knowledge Base/raw/115-kostopoulos-2020-akkermansia-muciniphila-uses-human-milk-oli\|raw/115-kostopoulos-2020-akkermansia-muciniphila-uses-human-milk-oli]] — *A. muciniphila*가 모유올리고당(HMO)을 이용해 영아기 초기 장 조건에서 증식 (*Sci. Rep.* 2020)
- [[Jay's Knowledge Base/raw/116-chiantera-2023-a-critical-perspective-on-the-supplementation\|raw/116-chiantera-2023-a-critical-perspective-on-the-supplementation]] — *A. muciniphila* 보충의 이익·위해 비판적 종설(IBD·감염·항생제 후 등 비유익 맥락 경고) (*Life* 2023)
- [[Jay's Knowledge Base/raw/117-effendi-2022-akkermansia-muciniphila-and-faecalibacterium-pr\|raw/117-effendi-2022-akkermansia-muciniphila-and-faecalibacterium-pr]] — *A. muciniphila*·*F. prausnitzii*의 면역관련 질환(SLE·HIV·건선·아토피) 항염 역할 종설 (*Microorganisms* 2022)
- [[Jay's Knowledge Base/raw/122-wang-2024-unveiling-akkermansia-muciniphila-akk11-a-comprehe\|raw/122-wang-2024-unveiling-akkermansia-muciniphila-akk11-a-comprehe]] — 영아 분리주 Akk11의 유전형·표현형 종합 안전성 평가(ANI 98.36%, ATCC BAA-835T 대비) (preprint 2024)
- [[Jay's Knowledge Base/raw/134-dang-2024-maternal-gut-microbiota-influence-stem-cell-functi\|raw/134-dang-2024-maternal-gut-microbiota-influence-stem-cell-functi]] — 모체 마이크로바이옴(*A. muciniphila* 조작)이 자손의 신경·장 줄기세포 기능·장기 건강에 영향 (*Cell Stem Cell* 2024)
- [[Jay's Knowledge Base/raw/136-bakshani-2025-carbohydrate-active-enzymes-from-akkermansia-m\|raw/136-bakshani-2025-carbohydrate-active-enzymes-from-akkermansia-m]] — *A. muciniphila*의 54 GH·11 sulfatase 등 CAZyme가 뮤신 O-글리칸을 완전 분해 (*Nature Microbiology* 2025)
- [[Jay's Knowledge Base/raw/138-niu-2024-molecular-mechanism-of-pasteurized-iakkermansia-muc\|raw/138-niu-2024-molecular-mechanism-of-pasteurized-iakkermansia-muc]] — 살균 *A. muciniphila*의 2형 당뇨 완화 분자기전을 병리 수준 다중오믹스로 규명 (*J. Agric. Food Chem.* 2024)
- [[Jay's Knowledge Base/raw/142-kumar-2024-iakkermansiai-beyond-muciniphila-emergence-of-new\|raw/142-kumar-2024-iakkermansiai-beyond-muciniphila-emergence-of-new]] — *Akkermansia* 속의 신종(*A. massiliensis* sp. nov.) 출현·균주 다양성 종설 (*Microbiome Res. Rep.* 2024; 283과 동일 논문)
- [[Jay's Knowledge Base/raw/146-zou-2020-engineered-akkermansia-muciniphila-a-promising-agen\|raw/146-zou-2020-engineered-akkermansia-muciniphila-a-promising-agen]] — engineered *A. muciniphila*(유전자편집 NGP) 질환 치료 잠재력 종설 (*Exp. Ther. Med.* 2020)
- [[Jay's Knowledge Base/raw/236-lee-2024-efficacy-of-etb-f01-heat-killed-akkermansia-mucinip\|raw/236-lee-2024-efficacy-of-etb-f01-heat-killed-akkermansia-mucinip]] — 가열사멸 *A. muciniphila* EB-AMDK19(ETB-F01) 호흡기 증상 환자 무작위 이중맹검 다기관 임상 (*Nutrients* 2024, 장-폐 축)
- [[Jay's Knowledge Base/raw/260-wade-2023-akkermansia-muciniphila-and-its-membrane-protein-a\|raw/260-wade-2023-akkermansia-muciniphila-and-its-membrane-protein-a]] — *A. muciniphila*·막단백질이 CREBH·miR-143/145 축으로 장 염증 완화·상피 창상 치유 (*J. Biomed. Sci.* 2023; 271과 동일 논문)
- [[Jay's Knowledge Base/raw/261-ashrafian-2021-comparative-effects-of-alive-and-pasteurized\|raw/261-ashrafian-2021-comparative-effects-of-alive-and-pasteurized]] — 정상식 마우스에서 생균·살균 *A. muciniphila*의 장 무결성·면역·지질·미생물 비교 효과 (*Sci. Rep.* 2021)
- [[Jay's Knowledge Base/raw/265-iwaza-2022-akkermansia-muciniphila-the-state-of-the-art-18-y\|raw/265-iwaza-2022-akkermansia-muciniphila-the-state-of-the-art-18-y]] — 분리 18년 *A. muciniphila* 분류·phylogroup·건강 효능 state-of-the-art 종설 (*Front. Gastroenterol.* 2022)
- [[Jay's Knowledge Base/raw/266-he-2023-iakkermansia-muciniphilai-protects-the-intestine-fro\|raw/266-he-2023-iakkermansia-muciniphilai-protects-the-intestine-fro]] — 방사선 유도 장손상 보호(프로피온산 분비) — 55와 동일 논문 (*Gut Microbes* 2023)
- [[Jay's Knowledge Base/raw/267-chelakkot-2018-akkermansia-muciniphila-derived-extracellular\|raw/267-chelakkot-2018-akkermansia-muciniphila-derived-extracellular]] — *A. muciniphila* 유래 세포외소포(EV)가 tight junction 조절로 장 투과성 개선 (*Exp. Mol. Med.* 2018)
- [[Jay's Knowledge Base/raw/268-kim-2021-mucin-degrader-iakkermansia-muciniphilai-accelerate\|raw/268-kim-2021-mucin-degrader-iakkermansia-muciniphilai-accelerate]] — *A. muciniphila*가 Lgr5⁺ 장줄기세포 매개 상피 발달(Paneth·goblet 분화) 가속 (*Gut Microbes* 2021)
- [[Jay's Knowledge Base/raw/269-shi-2022-pasteurized-akkermansia-muciniphila-ameliorate-the\|raw/269-shi-2022-pasteurized-akkermansia-muciniphila-ameliorate-the]] — 살균 *A. muciniphila*가 Caco-2에서 TLR2 경유 AMPK·NF-κB 조절로 LPS 유도 장벽 손상 완화 (*Nutrients* 2022)
- [[Jay's Knowledge Base/raw/270-meynier-2024-pasteurized-iakkermansia-muciniphilai-improves\|raw/270-meynier-2024-pasteurized-iakkermansia-muciniphilai-improves]] — 살균 *A. muciniphila*가 두 IBS 마우스 모델에서 IBS 유사 증상·관련 행동장애 완화 (*Gut Microbes* 2024)
- [[Jay's Knowledge Base/raw/271-wade-2023-akkermansia-muciniphila-and-its-membrane-protein-a\|raw/271-wade-2023-akkermansia-muciniphila-and-its-membrane-protein-a]] — CREBH·miR-143/145 축 장 염증 완화·창상 치유 — 260과 동일 논문 (*J. Biomed. Sci.* 2023)
- [[Jay's Knowledge Base/raw/272-lugt-2019-akkermansia-muciniphila-ameliorates-the-age-relate\|raw/272-lugt-2019-akkermansia-muciniphila-ameliorates-the-age-relate]] — *A. muciniphila*가 가속노화 *Ercc1⁻/Δ7* 마우스의 연령 관련 결장 점액층 두께 감소 회복·면역 활성화 완화 (*Immunity & Ageing* 2019)
- [[Jay's Knowledge Base/raw/273-kang-2024-the-secreted-protein-amuc-1409-from-akkermansia-mu\|raw/273-kang-2024-the-secreted-protein-amuc-1409-from-akkermansia-mu]] — 분비 단백질 Amuc_1409 장줄기세포 조절 — 86과 동일 논문 (*Nature Communications* 2024)
- [[Jay's Knowledge Base/raw/274-dao-2016-iakkermansia-muciniphilai-and-improved-metabolic-he\|raw/274-dao-2016-iakkermansia-muciniphilai-and-improved-metabolic-he]] — 비만 식이중재 코호트에서 기저 *A. muciniphila* 풍부도가 대사 개선·미생물 유전자 풍부도와 연관 (*Gut* 2016, responder 인체 근거)
- [[Jay's Knowledge Base/raw/275-depommier-2019-supplementation-with-akkermansia-muciniphila\|raw/275-depommier-2019-supplementation-with-akkermansia-muciniphila]] — 과체중·비만 자원자 *A. muciniphila* 보충 proof-of-concept 탐색 RCT, 살균형 인슐린 감수성 개선 (*Nature Medicine* 2019)
- [[Jay's Knowledge Base/raw/276-xue-2023-the-effects-of-live-and-pasteurized-iakkermansia-mu\|raw/276-xue-2023-the-effects-of-live-and-pasteurized-iakkermansia-mu]] — 생균·살균 *A. muciniphila*의 DSS-UC·미생물·대사체 비교(살균형 우수) (*Food & Function* 2023)
- [[Jay's Knowledge Base/raw/277-liu-2024-akkermansia-muciniphila-protects-against-antibiotic\|raw/277-liu-2024-akkermansia-muciniphila-protects-against-antibiotic]] — 살균 *A. muciniphila*·Amuc_1100이 항생제 관련 설사(AAD) 마우스 보호 (*Probiotics Antimicrob. Proteins* 2024)
- [[Jay's Knowledge Base/raw/278-fakhriravari-2025-the-role-of-akkermansia-muciniphila-in-hum\|raw/278-fakhriravari-2025-the-role-of-akkermansia-muciniphila-in-hum]] — *A. muciniphila* 인체 건강 임상 종설(관찰·전임상 종합, 점액·내독소·SCFA 기전) (preprint 2025)
- [[Jay's Knowledge Base/raw/279-soheilipour-2025-the-pathobiont-role-of-akkermansia-muciniph\|raw/279-soheilipour-2025-the-pathobiont-role-of-akkermansia-muciniph]] — 대장암(CRC)에서 *A. muciniphila*의 맥락 의존적·이중적 pathobiont 역할 체계적 고찰 (*BMC Gastroenterol.* 2025)
- [[Jay's Knowledge Base/raw/280-miranda-2024-a-next-generation-bacteria-akkermansia-muciniph\|raw/280-miranda-2024-a-next-generation-bacteria-akkermansia-muciniph]] — *A. muciniphila* BAA-835의 OVA 유도 식품알레르기 마우스 프로·포스트바이오틱 잠재력 (*Probiotics Antimicrob. Proteins* 2024)
- [[Jay's Knowledge Base/raw/281-du-2024-live-and-pasteurized-akkermansia-muciniphila-amelior\|raw/281-du-2024-live-and-pasteurized-akkermansia-muciniphila-amelior]] — 생균·살균 *A. muciniphila*가 db/db 마우스 당뇨성 인지장애를 미생물·대사산물 조절로 개선 (*Exp. Neurol.* 2024)
- [[Jay's Knowledge Base/raw/283-kumar-2024-iakkermansiai-beyond-muciniphila-emergence-of-new\|raw/283-kumar-2024-iakkermansiai-beyond-muciniphila-emergence-of-new]] — *Akkermansia* 신종·다양성 종설 — 142와 동일 논문 (*Microbiome Res. Rep.* 2024)
- [[Jay's Knowledge Base/raw/284-ndongo-2022-reclassification-of-eight-akkermansia-muciniphil\|raw/284-ndongo-2022-reclassification-of-eight-akkermansia-muciniphil]] — 8개 균주 재분류, *A. massiliensis* sp. nov.·*Candidatus* A. timonensis 기재 (dDDH) (*Sci. Rep.* 2022)
- [[Jay's Knowledge Base/raw/285-han-2025-antibiotic-associated-changes-in-akkermansia-mucini\|raw/285-han-2025-antibiotic-associated-changes-in-akkermansia-mucini]] — 페니실린 노출이 *A. muciniphila* 변이주를 선택해 숙주 대사 효과를 변질(유익→비유익) (*Microbiome* 2025)
- [[Jay's Knowledge Base/raw/292-chang-2026-extracellular-vesicles-from-akkermansia-muciniphi\|raw/292-chang-2026-extracellular-vesicles-from-akkermansia-muciniphi]] — *A. muciniphila* EV가 STZ 유도 당뇨 마우스의 포도당 항상성·산화 스트레스·면역 관용 조절로 보호 (*Front. Immunol.* 2026)
- [[Jay's Knowledge Base/raw/536-chen-2026-akkermansia-muciniphila-derived-extracellular-vesicles\|raw/536-chen-2026-akkermansia-muciniphila-derived-extracellular-vesicles]] — AmEV가 DSS-UC 마우스의 대장염·인지장애를 동시 회복: 장+BBB tight junction 회복·해마 신경염증 억제·*Bifidobacterium*↑/병원성↓·SCFA 회복·**트립토판/5-HT 양방향 재프로그래밍**·**Amuc_1100의 해마 직접 전달** (*Gut Microbes* 2026, IBD-CNS dual indication 분자 근거)
- [[Jay's Knowledge Base/raw/539-menadi-2026-synergistic-anticancer-effects-of-akkermansia\|raw/539-menadi-2026-synergistic-anticancer-effects-of-akkermansia]] — *A. muciniphila* 동결건조 추출물의 HT29·HCT116·SW620 CRC 세포 비교 세포독성, **BAX↑/BCL2↓ 의존 미토콘드리아 apoptosis**, 정상 Hs738 보호, **5-FU 시너지**로 용량 감량 가능성, 음의 zeta potential 막 표적성 (*Cell Biochem. Funct.* 2026)
