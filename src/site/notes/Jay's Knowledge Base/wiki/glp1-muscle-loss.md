---
{"dg-publish":true,"permalink":"/jay-s-knowledge-base/wiki/glp1-muscle-loss/","dg-note-properties":{}}
---


# GLP-1 수용체 작용제와 근손실

GLP-1 수용체 작용제(semaglutide, tirzepatide 등)는 비만 치료에서 15~25%의 체중 감량을 달성하지만, 감량분의 **25~40%가 제지방량(lean mass) 손실**에서 비롯된다. 이 문제를 해결하기 위해 ActRII 경로 차단 항체(bimagrumab, trevogrumab, apitegromab)를 병용하는 전략이 빠르게 발전하고 있으며, 마이크로바이옴 기반 접근(포스트바이오틱 companion)이 새로운 대안으로 부상하고 있다.

---

## GLP-1 유도 근손실의 규모

| 임상 | 약물 | 기간 | 제지방량 손실 | 전체 감량 대비 비율 |
|------|------|------|-------------|-------------------|
| STEP 1 DXA 하위연구 | Semaglutide 2.4 mg | 68주 | −5.26 kg (9.7%) | 34~45% |
| SURMOUNT-1 DXA 하위연구 | Tirzepatide | 72주 | −5.6 kg | ~25% |
| 메타분석 (22 RCTs, 2,258명) | GLP-1RA 전체 | — | — | ~25% (대조군 대비) |

### 왜 위험한가

- **60세 이상 비만 인구 40%** — 이미 근감소증 위험군에서 추가 근손실
- GLP-1 사용자의 **46~65%가 12개월 내 중단** → 중단 후 체중 반등은 대부분 지방(근육 아님)
- STEP-10: 중단 28주 후 **감량분의 40% 이상 반등**, SURMOUNT-4: 52주 후 **50% 이상 반등**
- 반복적 on-off 사이클 → 점진적 체성분 악화 ("같은 체중이라도 대사적으로 더 불건강")

---

## ActRII 경로: 핵심 신호 전달

ActRII(Activin Type II Receptor) → SMAD2/3 경로는 골격근 질량의 **마스터 음성 조절자**이다.

1. **Myostatin**(GDF-8), Activin A/B, GDF11이 ActRIIA/IIB에 결합
2. Type I 수용체(ALK4/ALK5) 인산화 → **SMAD2/3 인산화** (Inman 2002, *Mol Pharmacol* — ALK5/ALK4/ALK7 선택적 저해제 SB-431542 특성 규명으로 경로 검증)
3. SMAD2/3·SMAD4 복합체가 핵으로 이동
4. E3 유비퀴틴 리가아제(**Atrogin-1, MuRF1**) 전사 활성화 → **근 sarcomeric 단백질 유비퀴틴화·분해** (Lokireddy 2011: SMAD3 → FOXO1 → Atrogin-1이 주 E3, MuRF1은 부차적 역할, Atrogin-1 녹다운 시 sarcomeric 단백질 손실 80% 회복)
5. 동시에 **PI3K/Akt/TORC1/p70S6K** 단백질 합성 경로 억제(Trendelenburg 2009) + **MyoD·Myf5·myogenin 하향**으로 근아세포 분화 차단(Langley 2002 — Smad3·MyoD 결합, Smad3 도미넌트-음성으로 구제 가능)

### 기전 근거 요약 (primary literature)

| 연도 | 1저자 / 저널 | 핵심 발견 |
|------|--------------|-----------|
| 2002 | Langley, *JBC* | Myostatin → **Smad3 → MyoD 하향** → 근아세포 분화 차단 ([[Jay's Knowledge Base/raw/496-langley-2002-myostatin-inhibits-myoblast-differentiation-by-down\|raw/496-langley-2002-myostatin-inhibits-myoblast-differentiation-by-down]]) |
| 2002 | Inman, *Mol Pharmacol* | SB-431542: ALK4/5/7 선택적 저해제, TGF-β/activin 특이성 검증 ([[Jay's Knowledge Base/raw/492-inman-2002-sb-431542-is-a-potent-and-specific-inhibitor-of\|raw/492-inman-2002-sb-431542-is-a-potent-and-specific-inhibitor-of]]) |
| 2009 | Sartori, *AJP Cell* | **Smad2/3가 성체 근섬유에서 근량 조절**; Smad2/3 억제 → 근비대(satellite cell 독립, mTOR 부분 의존). Myostatin과 Akt 경로의 교차 ([[Jay's Knowledge Base/raw/502-sartori-2009-smad2-and-3-transcription-factors-control-muscle-mass\|raw/502-sartori-2009-smad2-and-3-transcription-factors-control-muscle-mass]]) |
| 2009 | Trendelenburg, *AJP Cell* | Myostatin → **Akt/TORC1/p70S6K 억제** → 분화·근관 크기 저하. RAPTOR 차단 시 SMAD2 인산화 증폭(경로 간 negative feedback) ([[Jay's Knowledge Base/raw/503-trendelenburg-2009-myostatin-reduces-akttorc1p70s6k-signaling-inhibiting\|raw/503-trendelenburg-2009-myostatin-reduces-akttorc1p70s6k-signaling-inhibiting]]) |
| 2011 | Lokireddy, *Mol Endocrinol* | Myostatin → Smad3 → FOXO1 → **Atrogin-1**이 sarcomeric 단백질 ubiquitination 주도, MuRF1은 부차적 ([[Jay's Knowledge Base/raw/498-lokireddy-2011-myostatin-induces-degradation-of-sarcomeric-proteins\|raw/498-lokireddy-2011-myostatin-induces-degradation-of-sarcomeric-proteins]]) |
| 2014 | **Lach-Trifilieff, *Mol Cell Biol*** | **BYM338(bimagrumab) — anti-ActRII 항체**가 Smad2/3 인산화 차단, myostatin 단독 저해 이상의 근비대 유도, 글루코코르티코이드 유도 근위축 보호. 현 bimagrumab 프로그램의 기반 ([[Jay's Knowledge Base/raw/494-lach-trifilieff-2014-an-antibody-blocking-activin-type-ii-receptors-induces\|raw/494-lach-trifilieff-2014-an-antibody-blocking-activin-type-ii-receptors-induces]]) |
| 2016 | Perie, *Biochem Biophys Rep* | **GASP-2** (endogenous myostatin inhibitor): 당화 여부와 무관하게 C2C12 증식·분화 촉진 → follistatin 외의 내인성 억제자 제안 ([[Jay's Knowledge Base/raw/499-perie-2016-enhancement-of-c2c12-myoblast-proliferation-and\|raw/499-perie-2016-enhancement-of-c2c12-myoblast-proliferation-and]]) |
| 2019 | Saneyasu, *J Poult Sci* | 조류 근관에서도 myostatin → Smad2/Atrogin-1 증가, 그러나 Akt/FOXO1 변화 없음 — **종간 차이 존재** ([[Jay's Knowledge Base/raw/501-saneyasu-2019-myostatin-increases-smad2-phosphorylation-and-atrogin\|raw/501-saneyasu-2019-myostatin-increases-smad2-phosphorylation-and-atrogin]]) |

ActRII는 **지방 조직에도 작용**하여 지방세포 분화·축적을 촉진 → 차단 시 근육 증가 + 지방 감소 동시 달성.

### 자연 억제자: Follistatin 및 GASP 계열

Follistatin은 myostatin에 직접 결합(KD ~584 pM)하여 ActRII 상호작용을 물리적으로 차단하는 **가장 강력한 내인성 억제자**이다. 살균 [[Jay's Knowledge Base/wiki/akkermansia-muciniphila\|akkermansia-muciniphila]] 포스트바이오틱이 follistatin 수치를 유의하게 상승시킨 것(RCT p=0.0063)은 이 경로와의 접점을 시사한다. 최근 **GASP-2**(GDF-associated serum protein 2) 역시 myostatin·GDF-11을 선택적으로 억제하는 다중 도메인 당단백질로 규명되어(Perie 2016), 포스트바이오틱 companion이 follistatin 외 내인성 억제자 네트워크를 활용할 가능성을 시사한다.

### In vitro 모델의 한계 (C2C12 주의사항)

BYM338·trevogrumab류의 전임상 스크리닝에 광범위하게 사용되는 **C2C12 근아세포 모델은 myostatin 연구에서 재현성 이슈**가 보고되어 있다:

- **Rodgers 2014** (*Endocrinology*): 진핵세포에서 생산한 재조합 myostatin은 C2C12 **증식을 억제가 아닌 자극**하며, primary myosatellite cell과 정반대 반응. 박테리아 유래 myostatin으로 얻은 기존 결과의 생리적 타당성에 문제 제기. ALK4/5 저해제(SB431542, SB505142)는 이 증식을 감쇠 ([[Jay's Knowledge Base/raw/500-rodgers-2014-myostatin-stimulates-not-inihibits-c2c12-myoblast\|raw/500-rodgers-2014-myostatin-stimulates-not-inihibits-c2c12-myoblast]])
- **Lautaoja 2020** (*Biomolecules*): C2C12가 **근관(myotube)으로 분화하면 myostatin canonical/noncanonical 신호 반응이 급감**(내생 follistatin 증가, activin 리간드 발현 변화가 원인). 동일 자극에 인간 CHQ 근관은 반응 유지 → C2C12 근관은 myostatin 신호 연구에 **준적정 모델**. 포스트바이오틱 등 후보물의 근관 단계 효능 평가 시 인간 primary/iPSC 유래 근관 병행 권장 ([[Jay's Knowledge Base/raw/497-lautaoja-2020-differentiation-of-murine-c2c12-myoblasts-strongly\|raw/497-lautaoja-2020-differentiation-of-murine-c2c12-myoblasts-strongly]])

> 💡 포스트바이오틱 기전 연구 설계 시 시사점: ① 근아세포 단계 vs 근관 단계 효과 구분, ② 진핵 유래 재조합 myostatin 사용, ③ 인간 primary/iPSC 유래 근관 병행 검증이 데이터 신뢰도와 규제 대응에 유리.

---

## ActRII 차단 + GLP-1 병용 임상 경쟁 현황 (2026)

| 프로그램 | 기업 | 기전 | GLP-1 파트너 | 제지방량 보존율 | 주요 우려 | 단계 |
|----------|------|------|-------------|---------------|----------|------|
| **Bimagrumab** | Eli Lilly ($19.25억 인수) | Anti-ActRIIA/IIB 수용체 | Semaglutide / Tirzepatide | **67%** | LDL↑, 간효소↑, 중단률 14~21% | Phase 2b 완료 |
| **Trevogrumab ± Garetosmab** | Regeneron | Anti-myostatin ± anti-activin A | Semaglutide | **51% (2제) / 81% (3제)** | 3제: 중단률 28%, 사망 2건 | Phase 2 |
| **Apitegromab** | Scholar Rock | Anti-pro/latent myostatin | Tirzepatide | **55%** | 추가 체중 감량 없음 | Phase 2 PoC |
| **Taldefgrobep** | Biohaven | Myostatin + ActRIIB-complex | 단독 우선 | 전임상만 | SMA Phase 3 실패 이력 | Phase 2 등록 |

### BELIEVE 임상 핵심 결과 (Bimagrumab + Semaglutide)

- 507명, 48주, 이중맹검 (Heymsfield et al., 2026, *Nature Medicine*; DOI: 10.1038/s41591-026-04204-0)
- 병용군: 체중 **22.1% 감량**, 그 중 **92.8%가 지방에서 감소** (semaglutide 단독: 71.8%)
- 병용군 제지방량 손실 **2.6%** vs semaglutide 단독 **7.9%**
- Bimagrumab 단독: 제지방량 기저선 대비 **+2.5% 증가**, 체중 감소는 100% 지방 유래
- 2026년 3월 *Nature Medicine* 게재

---

## GLP-1 Companion 서플리먼트 시장

| 지표 | 수치 |
|------|------|
| 시장 규모 (2025) | **$42억** |
| 시장 규모 (2030E) | **$84억** (CAGR 14.9%) |
| 시장 규모 (2035E) | **$130억** (CAGR 12.2%) |
| GLP-1 관련 서플리먼트 성장률 | **CAGR 124%** (2025-2026) |

### 학술 연구 관심도

GLP-1RA **부작용 연구 자체가 빠르게 성장** 중. Scopus 기반 서지 계량 분석(2006–2025)에서 1,075편의 논문이 389개 저널에 게재, **연평균 32.06% 증가**, 85개국 6,068명 저자 참여, 국제 공저율 34.23%. 출판 상위국은 **미국(30.5%) · 영국(10.6%) · 덴마크(7.8%)**, 기관 기여도는 **Novo Nordisk(60편, 11,207회 인용) · Eli Lilly(45편, 9,948회 인용)**가 압도적이며, 핵심 저널은 *Diabetes, Obesity and Metabolism*(106편), *Diabetes Care*, *Lancet Diabetes & Endocrinology*. 근손실·근감소증 등 체성분 부작용 영역은 이 거대한 안전성 연구 흐름의 한 축으로, 학계·산업계 모두 추적 가치가 빠르게 높아지는 중 (Abdelrahman 2026, *INQUIRY*).

- Novo Nordisk, Eli Lilly 모두 서플리먼트 companion 전략 미보유 → **white space**
- Lilly는 2026년 4월 **Centessa Pharmaceuticals를 $63억에 인수**, orexin 수용체 2 작용제(ORX750 등) 파이프라인 확보. GLP-1로 구축한 DTC 인프라를 orexin 약물에도 활용할 가능성이 제기됨 ([[Jay's Knowledge Base/raw/476-bayer-2026-eli-lilly-centessa-orexin-acquisition\|출처]])
- 현재 companion 제품은 프로틴(43%), 소화 건강(프로바이오틱) 순
- Walmart "GLP-1 Support" 카테고리 신설, Nature Made GLP-1 Companion Health Pack 출시
- **"체중 감량의 질(quality of weight loss)"** 이 새로운 경쟁 축으로 확립

### 마이크로바이옴 기반 companion 접근

항체 의약품($수천/월)과 달리 포스트바이오틱([[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]]) companion은:
- 경구, 1/100 비용, 비면역원성
- [[Jay's Knowledge Base/wiki/short-chain-fatty-acids\|short-chain-fatty-acids]] (SCFA) → Akt/mTOR 활성화로 SMAD2/3 매개 근위축에 대항
- 장 장벽 강화 → LPS 전위 감소 → myostatin 발현 유도 염증 차단
- [[Jay's Knowledge Base/wiki/akkermansia-muciniphila\|akkermansia-muciniphila]]의 세포외소포가 C2C12 근아세포에서 S6K1, 4EBP1 인산화 직접 활성화
- 살균 *A. muciniphila* RCT에서 follistatin 유의 상승(myostatin 격리), 하지 근력·peak torque 개선 (RCT 1·2)

### 내인성 GLP-1 분비 자극 — 별도의 차별 기전 (Yoon 2021 foundational)

GLP-1RA(semaglutide·tirzepatide)가 **외인성 호르몬 모방약**인 반면, *A. muciniphila*는 **장 L-cell의 GLP-1 분비를 직접 유도하는 분비 단백질**을 갖는다는 사실이 분리 단백질 수준에서 동정되어 있다 ([[Jay's Knowledge Base/raw/513-yoon-2021-akkermansia-muciniphila-secretes-a-glucagon-like\|Yoon et al., 2021, *Nature Microbiology*]]). 마우스에서 이 단백질 보충이 포도당 항상성을 개선하고 대사질환을 완화함이 확인됨.

| 구분 | GLP-1RA (외인성) | *A. muciniphila* 유래 인자 (내인성) |
|------|-----------------|------------------------------------|
| 작용 방식 | GLP-1 수용체 직접 자극 | 장 L-cell의 내인성 GLP-1 분비 자극 |
| 약효 지속 | 약효 반감기에 의존 | 일상적 식이/투여로 지속 가능 |
| 중단 후 반등 | 50%+ 반등 ([[Jay's Knowledge Base/wiki/obesity-body-composition\|PTER 항목]]) | 분비 자극이 유지되면 반등 완화 가능성 |
| 근손실 | 대규모 lean mass 손실 | 근육-장 axis (follistatin↑·EV·SCFA)로 보호 시도 |

**시사점**: Gao 2026 (db/db + Akk11 + semaglutide)에서 관찰된 **"병용 시 혈중 GLP-1 추가 증가"** 결과는 본 Yoon 2021의 분비 단백질 기전으로 설명 가능. → Akk 포스트바이오틱이 근손실 보존 외에도 **장 내인성 GLP-1 분비 자극**이라는 별도의 합리적 기전을 통해 GLP-1 효능을 보강 또는 중단 후 효과를 연장시킬 가능성을 제시. companion 포지셔닝의 second pillar.

> ⚠️ **자주 인용되는 Gao 2026 (db/db 마우스 + Akk11 + semaglutide) 데이터에 대한 주의**: 본 논문은 GLP-1RA + AKK 병용의 **대사·간지질 개선**은 강하게 지지하나, **"근손실 보존" 근거로는 사용할 수 없다**. 동일 실험에서 lean mass는 병용군에서 GLP-1RA 단독 대비 **추가 감소**(p<0.01)했으며, 측정 장비(Bruker Minispec LF50, TD-NMR)는 골격근과 장기(특히 간)를 분리하지 못한다. 같은 군에서 간 무게가 유의 감소(p<0.001)했으므로 lean mass 변화가 골격근 손실인지 간지방 해소인지 현 데이터로 구별 불가. "Synergy"의 2-factor ANOVA interaction 검정도 부재. AKK의 근육 보존 가설은 **follistatin RCT·EV·SCFA 경로** 같은 별도 근거 또는 DEXA/MRI 기반 후속 연구로 입증되어야 함 (상세 [[Jay's Knowledge Base/wiki/akkermansia-muciniphila\|akkermansia-muciniphila]] §2-1).

### GLP-1 중단 후 반등 방지 기전 — PTER 억제

근손실과 별개로 GLP-1의 또 다른 임상 공백인 **중단 후 체중 반등(50% 이상)**을 겨냥한 저분자 접근이 부상. Fu (2026)는 포식억제 대사체 N-acetyltaurine을 분해하는 PTER(phosphotriesterase-related)의 결정구조에서 HDAC 유사 포켓을 발견, 기질경쟁형 억제제 **PTERi**를 개발(nanomolar 효력, HDAC 대비 >100배 선택성). DIO 마우스에서 단독 투여 시 섭식 감소, GLP1-RA 병용 시 **체중 감량 강화**, GLP1-RA **중단 후 체중 재증가 예방** 효과 → ActRII 계열(근육 보존)과 다른 축의 companion 후보로, SCFA-HDAC 축과 개념적으로 연결(상세 [[Jay's Knowledge Base/wiki/obesity-body-composition\|obesity-body-composition]]).

### 경구 GLP-1 작용제로의 전환 유지 — Orforglipron ATTAIN-MAINTAIN (2026)

Eli Lilly의 **orforglipron** (경구·1일 1회·비펩타이드 GLP-1 작용제)은 SURMOUNT-5에서 주사형(tirzepatide·semaglutide)으로 감량한 환자가 경구 전환 시 **체중 감량의 74.7~79.3%를 52주간 유지**(위약 37.6~49.2%, P<0.001)함을 phase 3b ATTAIN-MAINTAIN에서 입증 (Aronne 2026, *Nature Medicine* — [[Jay's Knowledge Base/raw/519-aronne-2026-orforglipron-for-maintenance-of-body-weight-reduction\|raw/519-aronne-2026-orforglipron-for-maintenance-of-body-weight-reduction]], n=376). 의미: (1) "주사 → 경구 전환"이라는 **약리학적 maintenance 옵션**의 등장. (2) 경구·비펩타이드·globally scalable → **GLP-1 사용 인구의 절대 규모 확대**, companion(근손실 보존·내인성 GLP-1 분비 자극) 시장의 잠재 환자 풀이 함께 커짐. (3) 다만 **체성분(lean mass) 평가변수는 abstract에 명시되지 않음** — 경구 전환이 근감소 우려를 해결한다는 근거는 부재하며, 동일 수용체 작용 기전상 근손실 위험은 지속될 가능성이 높음. → ActRII 차단·포스트바이오틱 companion의 적용 범위는 **주사형뿐 아니라 경구 GLP-1RA 인구까지 확장**된다고 보아야 함.

---

## 관련 문서

- [[Jay's Knowledge Base/wiki/gut-muscle-axis\|gut-muscle-axis]] — 장-근육 축 기전 상세
- [[Jay's Knowledge Base/wiki/akkermansia-muciniphila\|akkermansia-muciniphila]] — Akkermansia 기반 GLP-1 companion 포지셔닝
- [[Jay's Knowledge Base/wiki/microbiome-therapeutics\|microbiome-therapeutics]] — 마이크로바이옴 치료제 전체 동향
- [[Jay's Knowledge Base/wiki/dysbiosis\|dysbiosis]] — 디스바이오시스와 근감소증의 악순환

## 출처

### 임상/시장
- [[Jay's Knowledge Base/raw/12-bimagrumab-believe-phase2b-glp1-muscle-preservation\|raw/12-bimagrumab-believe-phase2b-glp1-muscle-preservation]]
- [[Jay's Knowledge Base/raw/13-hb05p-actrii-pathway-literature-survey-and-market\|raw/13-hb05p-actrii-pathway-literature-survey-and-market]]
- [[Jay's Knowledge Base/raw/14-hb05p-glp1-companion-strategic-positioning\|raw/14-hb05p-glp1-companion-strategic-positioning]]
- [[Jay's Knowledge Base/raw/295-heymsfield-2026-bimagrumab-plus-semaglutide-alone-or-in-combination-for-the\|raw/295-heymsfield-2026-bimagrumab-plus-semaglutide-alone-or-in-combination-for-the]]
- [[Jay's Knowledge Base/raw/476-bayer-2026-eli-lilly-centessa-orexin-acquisition\|raw/476-bayer-2026-eli-lilly-centessa-orexin-acquisition]]
- [[Jay's Knowledge Base/raw/478-sharma-2026-dr-reddys-beyond-the-pill-semaglutide\|raw/478-sharma-2026-dr-reddys-beyond-the-pill-semaglutide]]
- [[Jay's Knowledge Base/raw/479-park-2026-samsung-biologics-glp1-cdmo-expansion\|raw/479-park-2026-samsung-biologics-glp1-cdmo-expansion]]
- [[Jay's Knowledge Base/raw/489-fu-2026-a-small-molecule-pter-selective-inhibitor-reduces-food\|raw/489-fu-2026-a-small-molecule-pter-selective-inhibitor-reduces-food]] — PTER 선택적 억제제 PTERi, GLP1-RA 병용 강화 및 중단 후 반등 방지
- [[Jay's Knowledge Base/raw/495-langer-2026-causes-of-sarcopenia-and-frailty-in-people-taking\|raw/495-langer-2026-causes-of-sarcopenia-and-frailty-in-people-taking]] — *Nat Rev Endocrinol* GLP1RA 복용 인구의 근감소증·쇠약(frailty) 원인 리뷰
- [[Jay's Knowledge Base/raw/505-abdelrahman-2026-mapping-global-research-on-adverse-effects-of-glp-1\|raw/505-abdelrahman-2026-mapping-global-research-on-adverse-effects-of-glp-1]] — GLP-1RA 부작용 글로벌 연구 동향 서지 계량 분석 (Scopus 2006–2025, 1,075편, 연 32% 성장, Novo Nordisk·Eli Lilly 기관 압도)
- [[Jay's Knowledge Base/raw/507-lee-2026-critical-reading-of-akk-glp1-paper\|raw/507-lee-2026-critical-reading-of-akk-glp1-paper]] — Gao 2026 (Akk + GLP-1RA db/db) 비판적 재검토. 체성분 도구(TD-NMR) 한계로 근손실 보존 주장 미입증을 정밀 분석
- [[Jay's Knowledge Base/raw/513-yoon-2021-akkermansia-muciniphila-secretes-a-glucagon-like\|raw/513-yoon-2021-akkermansia-muciniphila-secretes-a-glucagon-like]] — *A. muciniphila* 분비 GLP-1 유도 단백질 동정 및 마우스 대사 개선 (*Nature Microbiology* 2021, foundational). 장 내인성 GLP-1 분비 자극 메커니즘의 분자적 근거
- [[Jay's Knowledge Base/raw/519-aronne-2026-orforglipron-for-maintenance-of-body-weight-reduction\|raw/519-aronne-2026-orforglipron-for-maintenance-of-body-weight-reduction]] — Orforglipron(경구 비펩타이드 GLP-1RA) ATTAIN-MAINTAIN phase 3b RCT (n=376, 52주, *Nature Medicine* 2026): 주사 GLP-1RA 감량 후 경구 전환 시 체중 감량 74.7~79.3% 유지 (NCT06584916). 경구 GLP-1 시장 확장 → companion 잠재 환자 풀 확대

### ActRII / SMAD2/3 기전 — primary literature
- [[Jay's Knowledge Base/raw/492-inman-2002-sb-431542-is-a-potent-and-specific-inhibitor-of\|raw/492-inman-2002-sb-431542-is-a-potent-and-specific-inhibitor-of]] — SB-431542 (ALK4/5/7 선택적 저해제)
- [[Jay's Knowledge Base/raw/494-lach-trifilieff-2014-an-antibody-blocking-activin-type-ii-receptors-induces\|raw/494-lach-trifilieff-2014-an-antibody-blocking-activin-type-ii-receptors-induces]] — **BYM338(bimagrumab) 기반 논문**
- [[Jay's Knowledge Base/raw/496-langley-2002-myostatin-inhibits-myoblast-differentiation-by-down\|raw/496-langley-2002-myostatin-inhibits-myoblast-differentiation-by-down]] — Myostatin·Smad3·MyoD
- [[Jay's Knowledge Base/raw/498-lokireddy-2011-myostatin-induces-degradation-of-sarcomeric-proteins\|raw/498-lokireddy-2011-myostatin-induces-degradation-of-sarcomeric-proteins]] — Smad3·FOXO1·Atrogin-1
- [[Jay's Knowledge Base/raw/499-perie-2016-enhancement-of-c2c12-myoblast-proliferation-and\|raw/499-perie-2016-enhancement-of-c2c12-myoblast-proliferation-and]] — GASP-2 endogenous inhibitor
- [[Jay's Knowledge Base/raw/501-saneyasu-2019-myostatin-increases-smad2-phosphorylation-and-atrogin\|raw/501-saneyasu-2019-myostatin-increases-smad2-phosphorylation-and-atrogin]] — 조류 근관에서의 종간 차이
- [[Jay's Knowledge Base/raw/502-sartori-2009-smad2-and-3-transcription-factors-control-muscle-mass\|raw/502-sartori-2009-smad2-and-3-transcription-factors-control-muscle-mass]] — Smad2/3 성체 근량 조절
- [[Jay's Knowledge Base/raw/503-trendelenburg-2009-myostatin-reduces-akttorc1p70s6k-signaling-inhibiting\|raw/503-trendelenburg-2009-myostatin-reduces-akttorc1p70s6k-signaling-inhibiting]] — Myostatin · Akt/TORC1/p70S6K

### In vitro 모델 한계
- [[Jay's Knowledge Base/raw/497-lautaoja-2020-differentiation-of-murine-c2c12-myoblasts-strongly\|raw/497-lautaoja-2020-differentiation-of-murine-c2c12-myoblasts-strongly]] — C2C12 근관의 myostatin 반응성 저하
- [[Jay's Knowledge Base/raw/500-rodgers-2014-myostatin-stimulates-not-inihibits-c2c12-myoblast\|raw/500-rodgers-2014-myostatin-stimulates-not-inihibits-c2c12-myoblast]] — 진핵 재조합 myostatin의 C2C12 증식 자극 역설
