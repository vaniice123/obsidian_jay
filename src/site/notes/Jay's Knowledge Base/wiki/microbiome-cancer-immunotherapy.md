---
{"dg-publish":true,"permalink":"/jay-s-knowledge-base/wiki/microbiome-cancer-immunotherapy/","dg-note-properties":{}}
---


# 마이크로바이옴과 암 면역치료

## 개요

장내 마이크로바이옴(gut microbiome)은 암의 발생, 진행, 그리고 면역치료 반응에 광범위한 영향을 미치는 것으로 밝혀지고 있다. 특히 대장암(colorectal cancer, CRC)에서는 *Fusobacterium nucleatum*의 농축과 *Akkermansia muciniphila*, *Roseburia intestinalis* 등 유익균의 감소가 일관되게 보고되며, 이러한 미생물 시그니처는 젊은 환자(young-onset CRC)와 고령 환자 모두에서 유사하게 나타난다(Qin et al., 2023).

장내 미생물이 항암 면역을 조절하는 핵심 기전으로는 단쇄지방산(SCFA) 생성을 통한 종양미세환경(tumor microenvironment, TME) 재편, 트립토판 대사 경로(AhR/β-catenin signaling) 억제, CD8+ T 세포 활성화, 그리고 장내-종양 내 미생물 간 크로스토크(crosstalk)가 제시된다. *A. muciniphila*의 외막 단백질 Amuc_1100이나 저온살균 균체는 colitis-associated CRC 모델에서 CD8+ T 세포를 통해 종양 성장을 억제하였고(Wang et al., 2020), *Roseburia intestinalis*가 생산하는 부티르산(butyrate)은 anti-PD-1 면역관문억제제의 효능을 증강시켜 MSI-low 종양에서도 반응을 유도하였다(Kang et al., 2023).

이러한 연구들은 프로바이오틱스, 식이 조절, 분변 미생물 이식(FMT) 등을 통한 마이크로바이옴 조절이 기존 항암 면역치료의 보조 전략으로 활용될 수 있음을 시사한다. 장내 미생물과 종양 내 미생물(intratumoral microbiome) 사이의 상호작용, 그리고 항생제 사용이 면역치료 반응에 미치는 영향 역시 활발히 연구되고 있다.

## 주요 내용/기전

- **SCFA에 의한 종양미세환경 조절**: 부티르산(butyrate), 프로피온산(propionate), 아세트산(acetate) 등 미생물 유래 SCFA가 히스톤 탈아세틸화효소(HDAC) 억제, 세포자멸사 유도, 항염증 면역세포 분화를 촉진하여 CRC를 억제한다 (Gomes et al., 2023)
- **Akkermansia muciniphila의 항암 기전**:
  - 외막 단백질 Amuc_1100이 CD8+ CTL을 활성화하고 종양 성장을 억제 (Wang et al., 2020)
  - AhR/β-catenin 경로를 통해 트립토판 대사를 억제하여 CRC 진행을 차단 (Zhang et al., 2023)
  - 장내 투여 시 종양 내 미생물 조성 및 대사체를 변화시키는 크로스토크 확인 — 폐암 모델에서도 항암 효과 (Zhu et al., 2023)
  - Anti-PD-L1 면역치료 효능 강화 (Hou et al., 2021; Chen et al., 2020)
  - Pentadecanoic acid (C15:0) 생성을 통한 항암 효과 (Xu et al., 2024)
  - **포스트바이오틱(살균체)의 균주별 세포독성 비교**: Kurt Cakmaktas et al. (2026, *J. Agric. Food Res.*)은 3개 *A. muciniphila* 균주 포스트바이오틱을 위암(AGS)·대장암(HCT116) 세포에 처리, MTT 대사활성을 **용량·시간 의존적으로 감소**시켰으며 규모는 유사하나 **균주 특이적 경향** 관찰. LC-QTOF-MS + ¹H NMR 통합 프로파일링으로 상피·redox 경로 관련 6개 단백질/대사체를 식별. 포스트바이오틱 균주 선택의 **합리적 criteria** 수립 근거를 제공
  - **5-FU 시너지 — BAX/BCL2 의존 apoptosis (Menadi 2026)**: Menadi & Cacan (*Cell Biochem. Funct.*)은 *A. muciniphila* 동결건조 추출물이 HT29·HCT116·SW620 CRC 세포주에서 **BAX↑/BCL2↓ 미토콘드리아 apoptosis**를 직접 활성화하며 (HT29 > HCT116 > SW620 감수성), 정상 Hs738 기질세포는 잘 견딤 → **암세포 선택적 세포독성**. 5-FU 병용 시 **시너지** → 5-FU 용량 감량으로 독성 완화 전략 제시. 강한 음의 zeta potential은 암세포 막 표적성을 시사. **공개 데이터셋 메타분석**에서 *A. muciniphila* 풍부도가 건강 → adenoma → CRC로 감소하다 진행기 종양에서 소폭 회복하는 비단조 패턴 확인 → 기존 Amuc_1100/CD8⁺ CTL·트립토판 축에 **추출물의 직접 종양세포 작용**이라는 별도 기전 축을 보탠다 ([[Jay's Knowledge Base/raw/539-menadi-2026-synergistic-anticancer-effects-of-akkermansia\|raw/539-menadi-2026-synergistic-anticancer-effects-of-akkermansia]])
- **MSS 대장암의 anti-PD-1 저항 극복 — TLR2/NF-κB → cGAS-STING 축 + phase 1 임상 (Jiang 2026, *Cell Host & Microbe*)**: 대장암의 **약 85%가 microsatellite stable(MSS)** 로 anti-PD-1에 **내재적 저항**을 보인다. 본 연구는 *A. muciniphila*(Akk) **경구 투여**가 MSS CRC 마우스 모델에서 종양 형성을 억제하고 종양미세환경을 재프로그래밍함을 보였다. 기전은 기존 Amuc_1100/CD8⁺ CTL 축과 구별되는 **선천면역 경유 캐스케이드**다 — Akk가 **TLR2/NF-κB 경로를 통해 대식세포의 efferocytosis(세포자멸사 세포 제거)를 약화** → **세포자멸사 암세포가 축적** → **cGAS-STING 경로 활성화** → **I형 인터페론 생산 증강** → **효과기 CD8⁺ T세포 활성화** → anti-PD-1 반응 개선.

  - **⛑ 인체 phase 1 임상 동반 (NCT06865521)**: 1차 이상 치료 경험이 있는 **전이성 MSS CRC** 환자에서 **Akk 프로바이오틱 + PD-1 항체** 병용. **안전성 양호**, **객관적 반응률(ORR) 19%**, 반응군에서 항종양 면역 증강 확인.
  - **💡 전략적 의미**: ① 마이크로바이옴 종양학에서 Akk 근거가 **전임상 → 인체 조기 임상**으로 넘어간 사례이며, 하필 **면역치료가 거의 듣지 않는 MSS 아형**(CRC의 대다수)을 표적했다. ② 기전이 **대식세포 → STING → I형 IFN**이라는 선천면역 축이므로, 위 Amuc_1100/CD8⁺ 축·트립토판 축·추출물 직접 세포독성(Menadi 2026)과 **중복되지 않는 네 번째 기전 축**이 추가된다. ③ 본 연구는 **생균(probiotic) 경구 투여**이며 **살균형·포스트바이오틱은 평가되지 않았다** — HB03/HB05P의 살균형 소재에 그대로 외삽할 수 없다(별도 검증 필요).
  - ⚠️ 한계: ORR 19%는 **단일군 phase 1 소규모**로 대조군이 없고, 균주 정보·용량·병용 PD-1 항체 종류는 초록 범위를 넘어 **본문 확인 필요**. 마우스 기전과 인체 반응의 인과 연결도 phase 1 수준에서는 상관 관찰이다 ([[Jay's Knowledge Base/raw/655-jiang-2026-akkermansia-muciniphila-attenuates-macrophage\|raw/655-jiang-2026-akkermansia-muciniphila-attenuates-macrophage]], *Cell Host & Microbe* 2026, DOI 10.1016/j.chom.2026.09.014, PMID 42887494)
- **Roseburia intestinalis와 면역관문억제제**: *R. intestinalis* 유래 부티르산이 TBX21 프로모터의 H3K27 아세틸화를 촉진하여 CD8+ T 세포의 세포독성을 증강시키고, anti-PD-1 효능을 부스팅 (Kang et al., 2023)
- **장내 미생물 시그니처와 CRC 진단**: 다국적 대규모 메타게놈 분석에서 *F. nucleatum*, *Parvimonas micra* 등의 CRC 연관 시그니처가 나이와 무관하게 일관됨 (Qin et al., 2023)
- **Fusobacterium nucleatum**: 특정 clade (Fna C2)가 CRC 조직에 선택적으로 농축 (Zepeda-Rivera et al., 2024)
- **CAR-T 세포 치료와 장내 미생물**: 장내 미생물 다양성이 CAR-T 치료 반응과 연관 (Asokan et al., 2023)
- **비타민 D와 미생물 시너지**: 비타민 D가 장내 미생물을 매개로 면역치료 반응을 개선할 가능성 (Franco et al., 2024)
- **Sodium butyrate + 화학항암제 병용**: 부티르산나트륨이 옥살리플라틴(oxaliplatin)과 시너지 효과를 보임 (Shuwen et al., 2023)
- **신바이오틱스에 의한 항암화학요법 부작용 완화**: 식도암 환자의 신보강 항암화학요법(neoadjuvant chemotherapy) 후향적 탐색 연구에서, 신바이오틱스(synbiotics) 투여군은 항암제 부작용(adverse events)이 경감되었으며 이 완화 효과가 특정 장내 미생물 조성과 연관됨이 관찰됨 — 미생물 조절이 항암 치료의 독성 관리 보조 전략이 될 가능성 (Sugimoto et al., 2023)
- **산소민감 Akk의 CRC 전달 제형 (Quah 2026)**: CRC 예방과 연관된 NGP인 *A. muciniphila*의 호기 사멸 문제를 알지네이트 마이크로캡슐화로 극복해 저장 안정성을 높인 전달 시스템 연구 — 항암 미생물의 제형·전달(formulation/delivery) 관점 ([[Jay's Knowledge Base/raw/534-quah-2026-microencapsulation-strategy-for-aerobic-cultivation-of\|raw/534-quah-2026-microencapsulation-strategy-for-aerobic-cultivation-of]]; 공정 상세 [[Jay's Knowledge Base/wiki/bioprocess-engineering\|bioprocess-engineering]])

## 암 악액질(cancer cachexia)과 장내 미생물 — 결과 미확보 · 모니터링

암 악액질(cancer cachexia)은 환자 생존과 삶의 질에 큰 영향을 미치지만 현행 치료로는 진행을 멈추지 못하며, **골격근 소모(skeletal muscle wasting)를 종양 진행(tumor progression)으로부터 분리(uncouple)** 할 수 있는 **숙주 표적(host-directed) 치료**의 임상적 필요가 크다. Youn et al. (2026, *Microbiome*, [[Jay's Knowledge Base/raw/623-youn-2026-micheliolide-ameliorates-colon-cancer-cachexia-by\|raw/623-youn-2026-micheliolide-ameliorates-colon-cancer-cachexia-by]])은 화합물 **micheliolide(MCL)** 가 ***Phocaeicola vulgatus*의 농축(enrichment)** 을 통해 **장내균총–면역 신호(gut microbiota–immune signaling)** 를 조절함으로써 대장암 악액질을 개선한다고 보고했으며, 서로 다른 종양 맥락(distinct tumor contexts)에 걸쳐 MCL의 치료 잠재력을 검토했다.

| 항목 | 내용 |
|------|------|
| 문헌 | Youn et al., 2026, *Microbiome* |
| 중재 | micheliolide (MCL) |
| 매개 균종 | *Phocaeicola vulgatus* (농축) |
| 제안 기전 축 | 장내균총 → 면역 신호(microbiota–immune signaling) 조절 |
| 표적 병태 | 대장암 악액질(colon cancer cachexia) |
| 치료 컨셉 | host-directed — 종양 진행과 근소모의 **분리(uncoupling)** |

> **상태: 결과 미확보 · 모니터링.** 현재 초록의 앞부분(배경·연구 목적)만 확보된 상태로, **구체적 결과 수치·검증 모델·면역세포 수준의 기전은 미확보**다. 본문 확보 후 보강 필요.

확보된 범위 내에서의 의미는 다음과 같다. 이 축은 [[Jay's Knowledge Base/wiki/gut-muscle-axis\|gut-muscle-axis]](장–근육 축)와 직접 연결되고, 근소모라는 결과 지표에서는 [[Jay's Knowledge Base/wiki/sarcopenia\|sarcopenia]]와도 접점을 갖는다. 면역관문억제제 병용처럼 **항암 효능 증강**을 노리는 기존 마이크로바이옴 종양학 흐름과 달리, **암 관련 근소모라는 숙주 측 합병증**을 미생물 조절로 다룬다는 점에서 적용 범위를 「반응률(response rate)」에서 「환자 기능·삶의 질」로 확장하는 사례다 (cf. 위 신바이오틱스의 항암화학요법 부작용 완화 항목). *Phocaeicola vulgatus*(구 *Bacteroides vulgatus*)는 [[Jay's Knowledge Base/wiki/next-generation-probiotics\|next-generation-probiotics]] 후보군과 계통적으로 인접한 Bacteroidetes 공생균으로, 저분자 화합물이 **특정 공생균을 선택적으로 농축**시켜 효과를 내는 「소재 × 표적균」 설계 사례로도 읽을 수 있다.

## ⚠️ 면역관련 이상반응(irAE)에서 *Akkermansia* 농축이 「위험 방향」으로 나타난 근거 (Patra 2026, *Cell*)

면역관문차단(immune checkpoint blockade, ICB)은 암 치료를 바꿨으나 **면역관련 이상반응(immune-related adverse events, irAEs)** 은 때로 치명적인 주요 한계로 남아 있고, 견고한 전임상 모델의 부재가 기전 규명을 가로막아 왔다. Patra et al. (2026, *Cell*, [[Jay's Knowledge Base/raw/664-patra-2026-lifestyle-induced-regulatory-t-cell-fragility-primes\|raw/664-patra-2026-lifestyle-induced-regulatory-t-cell-fragility-primes]], DOI 10.1016/j.cell.2026.09.055)는 **식이 유래 대사·미생물 변화가 사람과 유사한 anti-PD-1 독성 감수성을 재현**하는 **LISA(lifestyle-induced susceptibility to irAEs) 모델**을 제시했다.

- **모델 특성**: 다장기 irAE(면역세포 침윤·사이토카인 생산)를 재현하며, 중증도는 **성별·연령·치료 방식·면역치료 반응 여부**에 따라 달라진다
- **🔴 핵심 기전 — *A. muciniphila* 농축이 표지가 된 디스바이오시스**: 저자들이 기술한 디스바이오시스는 ***Akkermansia muciniphila* 농축(enrichment)으로 표지(marked)** 되며, 이것이 비정상적 면역 활성화를 동반하면서 **조절 T세포(Treg) 취약성(fragility)** 과 **CD8⁺ 세포독성 효과기 집단**을 유도한다. 두 소견은 **면역치료 유발 대장염(irColitis) 환자에서도 관찰**되었다
- **가역성**: 식이 되돌림(dietary reversal), 대사체 보충, Treg에서의 **IFN-γ 생산 또는 신호 차단**이 Treg 안정성을 회복시키고 염증을 해소했다
- **인체→마우스 분변 이식**: 사람 분변 미생물 이식이 **수용 마우스의 식이와 상호작용**하여 감수성을 결정했다 — 미생물 단독이 아니라 **식이 × 미생물**의 교호작용

### 💡 전략적 해석 — 본 문서 서사에 대한 중요한 경계 조건

본 문서의 기존 서사는 ***A. muciniphila*가 항암 면역을 증강한다**는 방향이었다(Amuc_1100/CD8⁺ CTL 축, TLR2→cGAS-STING 축, 추출물 직접 세포독성, anti-PD-L1 효능 강화 등). 본 연구는 **같은 균종의 농축이 irAE 감수성 쪽에서는 위험 표지로 나타난** 사례이므로, 다음과 같이 읽어야 한다.

1. **「효능」과 「독성」은 분리된 결과 지표다**: ICB 반응률 증강 근거가 곧 안전성 근거가 되지 않는다. *A. muciniphila* 농축이 **효능 쪽에서 유리, 독성 쪽에서 불리**할 수 있다는 가능성이 제기된다 — 이는 [[Jay's Knowledge Base/wiki/akkermansia-clinical-evidence\|akkermansia-clinical-evidence]]의 Rojas 2026(용량·조건 의존적 양면성)이 지적한 「경계 조건 명시」 요구와 같은 방향이다.
2. **⚠️ 인과 방향은 본 초록으로 확정되지 않는다**: 초록은 Akk 농축을 디스바이오시스의 **표지(marked by)** 로 기술하며, **Akk 투여가 irAE를 유발한다는 개입 실험은 초록 범위에서 확인되지 않는다**(확인 필요). 즉 「동반 소견」과 「원인」을 구분해야 하며, 보충 개입(supplementation)의 안전성에 직접 외삽할 수 없다.
3. **상류 결정인자는 식이**: 가역성이 식이 되돌림·대사체 보충으로 확보되었고 FMT 효과도 수용자 식이에 의존했다 — 미생물 조성 자체보다 **식이-대사 맥락**이 상류라는 틀이다 (cf. [[Jay's Knowledge Base/wiki/akkermansia-clinical-evidence\|akkermansia-clinical-evidence]] Rojas 2026의 동일 지적).
4. **개발 관점의 과제**: HB03 등 **항암 영역에서 Akk 계열 소재를 ICB 병용으로 포지셔닝할 경우, 효능 지표와 함께 irAE 관련 안전성 지표(Treg 안정성·IFN-γ·대장염 소견)를 평가 설계에 포함**해야 한다는 근거가 된다. 본 연구는 **생균/살균 구분이나 특정 균주 투여를 평가하지 않았으므로**(내인성 농축 관찰) 살균형 소재에 그대로 적용되는지는 **별도 검증이 필요**하다.

## 소화기암에서 마이크로바이옴–ICI 시그니처의 재현성과 번역 준비도 (Sagawa 2026, *Current Oncology Reports*)

장내 미생물 특징은 **면역관문억제제(ICI) 결과와 연관**되어 왔으나, 이 시그니처가 **소화기(GI) 종양 유형·치료 레지멘·인구집단에 걸쳐 견고한지(robust)는 불확실**하다. Sagawa et al. ([[Jay's Knowledge Base/raw/665-sagawa-2026-gut-microbiome-signatures-and-immune-checkpoint\|raw/665-sagawa-2026-gut-microbiome-signatures-and-immune-checkpoint]], DOI 10.1007/s11912-026-01853-9)는 **비판적 내러티브 리뷰(critical narrative review)** 로 ① 인체 근거, ② 실험적 기전, ③ 종단 샘플링(longitudinal sampling), ④ **임상 적용(clinical implementation)에 필요한 기준**을 평가했다.

> **상태: 결과·결론 미확보 · 모니터링.** 확보된 초록은 **연구 목적과 평가 범위까지**이며, 저자들이 제시한 **구체적 번역 기준(criteria)·재현성 판정·권고 사항은 미확보**다. 본문 확보 후 보강 필요.

**확보 범위 내 의미**: 본 문서가 축적한 개별 기전·균종 근거(위 MSS CRC phase 1, Akk 항암 축, *R. intestinalis* 부티르산 축 등)에 대해 **「종양 유형·레지멘·인구를 넘어 재현되는가」라는 외부 타당성 질문을 정면으로 제기**하는 리뷰다. 소화기암 중심이므로 **CRC 적응증([[Jay's Knowledge Base/wiki/akkermansia-indications-applications\|akkermansia-indications-applications]]·HB03/HB05P CRC 평가)과 직접 겹치며**, 번역 기준 항목이 확보되면 **임상 개발 계획의 체크리스트로 활용 가치가 높다**. cf. [[Jay's Knowledge Base/wiki/microbiome-therapeutics\|microbiome-therapeutics]]의 번역 장벽 종설(Fassarella 2026·Gilbert 2025).

## 관련 raw/ 소스

- [[Jay's Knowledge Base/raw/22-gomes-2023-modulation-of-the-tumor-microenvironment-by-micro\|raw/22-gomes-2023-modulation-of-the-tumor-microenvironment-by-micro]]
- [[Jay's Knowledge Base/raw/24-peng-2020-the-gut-microbiome-is-associated-with-clinical-res\|raw/24-peng-2020-the-gut-microbiome-is-associated-with-clinical-res]]
- [[Jay's Knowledge Base/raw/40-zhang-2023-iakkermansia-muciniphilai-inhibits-tryptophan-met\|raw/40-zhang-2023-iakkermansia-muciniphilai-inhibits-tryptophan-met]]
- [[Jay's Knowledge Base/raw/50-queen-2023-understanding-the-mechanisms-and-translational-im\|raw/50-queen-2023-understanding-the-mechanisms-and-translational-im]]
- [[Jay's Knowledge Base/raw/54-jiang-2023-microbiota-a-key-factor-affecting-and-regulating\|raw/54-jiang-2023-microbiota-a-key-factor-affecting-and-regulating]]
- [[Jay's Knowledge Base/raw/58-anderson-2023-the-role-of-the-gut-microbiome-in-cancer-a-rev\|raw/58-anderson-2023-the-role-of-the-gut-microbiome-in-cancer-a-rev]]
- [[Jay's Knowledge Base/raw/59-liu-2023-gut-microbial-structural-variation-associates-with\|raw/59-liu-2023-gut-microbial-structural-variation-associates-with]]
- [[Jay's Knowledge Base/raw/64-rahman-2023-colorectal-disease-and-the-gut-microbiome\|raw/64-rahman-2023-colorectal-disease-and-the-gut-microbiome]]
- [[Jay's Knowledge Base/raw/66-jiang-2024-gut-microbiota-influences-the-efficiency-of-immun\|raw/66-jiang-2024-gut-microbiota-influences-the-efficiency-of-immun]]
- [[Jay's Knowledge Base/raw/75-schorr-2023-intracellular-bacteria-in-cancerprospects-and-de\|raw/75-schorr-2023-intracellular-bacteria-in-cancerprospects-and-de]]
- [[Jay's Knowledge Base/raw/76-yadav-2024-gut-microbiomecolorectal-cancer-relationship\|raw/76-yadav-2024-gut-microbiomecolorectal-cancer-relationship]]
- [[Jay's Knowledge Base/raw/77-asokan-2023-car-t-cell-therapy-and-the-gut-microbiota\|raw/77-asokan-2023-car-t-cell-therapy-and-the-gut-microbiota]]
- [[Jay's Knowledge Base/raw/79-faghfuri-2024-the-role-of-akkermansia-muciniphila-in-colorec\|raw/79-faghfuri-2024-the-role-of-akkermansia-muciniphila-in-colorec]]
- [[Jay's Knowledge Base/raw/80-zepeda-rivera-2024-a-distinct-fusobacterium-nucleatum-clade\|raw/80-zepeda-rivera-2024-a-distinct-fusobacterium-nucleatum-clade]]
- [[Jay's Knowledge Base/raw/82-shuwen-2023-synergistic-effect-of-sodium-butyrate-and-oxalip\|raw/82-shuwen-2023-synergistic-effect-of-sodium-butyrate-and-oxalip]]
- [[Jay's Knowledge Base/raw/83-an-2016-combination-therapy-of-lactobacillus-plantarum-super\|raw/83-an-2016-combination-therapy-of-lactobacillus-plantarum-super]]
- [[Jay's Knowledge Base/raw/90-qin-2023-consistent-signatures-in-the-human-gut-microbiome-o\|raw/90-qin-2023-consistent-signatures-in-the-human-gut-microbiome-o]]
- [[Jay's Knowledge Base/raw/91-franco-2024-microbes-and-vitamin-d-aid-immunotherapy\|raw/91-franco-2024-microbes-and-vitamin-d-aid-immunotherapy]]
- [[Jay's Knowledge Base/raw/105-yang-2024-crosstalk-between-gut-microbiota-and-cancer-chemot\|raw/105-yang-2024-crosstalk-between-gut-microbiota-and-cancer-chemot]]
- [[Jay's Knowledge Base/raw/108-wang-2020-a-purified-membrane-protein-from-iakkermansia-muci\|raw/108-wang-2020-a-purified-membrane-protein-from-iakkermansia-muci]]
- [[Jay's Knowledge Base/raw/109-luo-2021-extracellular-vesicles-from-akkermansia-muciniphila\|raw/109-luo-2021-extracellular-vesicles-from-akkermansia-muciniphila]]
- [[Jay's Knowledge Base/raw/110-hou-2021-akkermansia-muciniphila-potentiates-the-antitumor-e\|raw/110-hou-2021-akkermansia-muciniphila-potentiates-the-antitumor-e]]
- [[Jay's Knowledge Base/raw/121-xu-2024-akkermansia-muciniphila-derived-pentadecanoic-acid-e\|raw/121-xu-2024-akkermansia-muciniphila-derived-pentadecanoic-acid-e]]
- [[Jay's Knowledge Base/raw/125-kim-2024-a-conserved-pilin-from-uncultured-gut-bacterial-cla\|raw/125-kim-2024-a-conserved-pilin-from-uncultured-gut-bacterial-cla]]
- [[Jay's Knowledge Base/raw/126-kim-2024-a-conserved-pilin-from-uncultured-gut-bacterial-cla\|raw/126-kim-2024-a-conserved-pilin-from-uncultured-gut-bacterial-cla]]
- [[Jay's Knowledge Base/raw/128-zhu-2023-microbiome-and-spatially-resolved-metabolomics-anal\|raw/128-zhu-2023-microbiome-and-spatially-resolved-metabolomics-anal]]
- [[Jay's Knowledge Base/raw/129-chen-2020-iakkermansia-muciniphilai-enhances-the-antitumor-e\|raw/129-chen-2020-iakkermansia-muciniphilai-enhances-the-antitumor-e]]
- [[Jay's Knowledge Base/raw/130-su-2022-commentary-intermittent-fasting-and-akkermansia-muci\|raw/130-su-2022-commentary-intermittent-fasting-and-akkermansia-muci]]
- [[Jay's Knowledge Base/raw/131-wang-2020-a-purified-membrane-protein-from-iakkermansia-muci\|raw/131-wang-2020-a-purified-membrane-protein-from-iakkermansia-muci]]
- [[Jay's Knowledge Base/raw/165-otsuka-2024-butyricimonas-is-a-key-gut-microbiome-component\|raw/165-otsuka-2024-butyricimonas-is-a-key-gut-microbiome-component]]
- [[Jay's Knowledge Base/raw/185-liu-2023-ieubacterium-rectalei-improves-the-efficacy-of-anti\|raw/185-liu-2023-ieubacterium-rectalei-improves-the-efficacy-of-anti]]
- [[Jay's Knowledge Base/raw/200-kang-2023-iroseburia-intestinalisi-generated-butyrate-boosts\|raw/200-kang-2023-iroseburia-intestinalisi-generated-butyrate-boosts]]
- [[Jay's Knowledge Base/raw/248-birebent-2025-surrogate-markers-of-intestinal-dysfunction-as\|raw/248-birebent-2025-surrogate-markers-of-intestinal-dysfunction-as]]
- [[Jay's Knowledge Base/raw/264-sun-2025-enhancing-immunotherapy-efficacy-in-nsclc-through-t\|raw/264-sun-2025-enhancing-immunotherapy-efficacy-in-nsclc-through-t]]
- [[Jay's Knowledge Base/raw/282-marcos-kovandzic-2025-gut-microbiota-modulation-through-iakk\|raw/282-marcos-kovandzic-2025-gut-microbiota-modulation-through-iakk]]
- [[Jay's Knowledge Base/raw/493-kurt-cakmaktas-2026-comparative-cytotoxicity-and-molecular-profiling-of\|raw/493-kurt-cakmaktas-2026-comparative-cytotoxicity-and-molecular-profiling-of]] — 3종 *A. muciniphila* 균주 포스트바이오틱의 AGS·HCT116 세포 비교 세포독성 + 프로테오믹스/메타볼로믹스 프로파일링
- [[Jay's Knowledge Base/raw/208-sugimoto-2023-gut-microbiota-associated-with-the-mitigation\|raw/208-sugimoto-2023-gut-microbiota-associated-with-the-mitigation]] — 식도암 신보강 항암화학요법 부작용을 완화하는 신바이오틱스와 연관 장내 미생물 (후향적 탐색 연구)
- [[Jay's Knowledge Base/raw/534-quah-2026-microencapsulation-strategy-for-aerobic-cultivation-of\|raw/534-quah-2026-microencapsulation-strategy-for-aerobic-cultivation-of]] — 산소 민감 *A. muciniphila*의 알지네이트 마이크로캡슐화 전달 시스템, CRC 중재 응용 (제형·전달 관점)
- [[Jay's Knowledge Base/raw/539-menadi-2026-synergistic-anticancer-effects-of-akkermansia\|raw/539-menadi-2026-synergistic-anticancer-effects-of-akkermansia]] — *A. muciniphila* 동결건조 추출물의 HT29·HCT116·SW620 CRC 세포 비교 세포독성·BAX/BCL2 의존 apoptosis·5-FU 시너지(*Cell Biochem. Funct.* 2026)
- [[Jay's Knowledge Base/raw/623-youn-2026-micheliolide-ameliorates-colon-cancer-cachexia-by\|raw/623-youn-2026-micheliolide-ameliorates-colon-cancer-cachexia-by]] — micheliolide(MCL)가 *Phocaeicola vulgatus* 농축을 통해 장내균총–면역 신호를 조절하여 대장암 악액질 개선; 종양 진행과 골격근 소모를 분리하는 host-directed 치료 관점 (*Microbiome* 2026). **초록 앞부분만 확보 — 결과 미확보 · 모니터링**
- [[Jay's Knowledge Base/raw/655-jiang-2026-akkermansia-muciniphila-attenuates-macrophage\|raw/655-jiang-2026-akkermansia-muciniphila-attenuates-macrophage]] — **MSS CRC(전체 CRC의 ~85%, anti-PD-1 내재 저항)에서 경구 Akk가 TLR2/NF-κB로 대식세포 efferocytosis 약화 → 세포자멸사 암세포 축적 → cGAS-STING → I형 IFN → CD8⁺ T세포 활성화**; **phase 1(NCT06865521, 전이성 MSS CRC, Akk 프로바이오틱 + PD-1 항체): 안전성 양호·ORR 19%** (Jiang et al., *Cell Host & Microbe* 2026, DOI 10.1016/j.chom.2026.09.014, PMID 42887494). ⚠️ 생균 경구 투여 — 살균형 미평가
- [[Jay's Knowledge Base/raw/664-patra-2026-lifestyle-induced-regulatory-t-cell-fragility-primes\|raw/664-patra-2026-lifestyle-induced-regulatory-t-cell-fragility-primes]] — **🔴 irAE 감수성 모델(LISA)**: 식이 유도 대사·미생물 변화가 사람 유사 anti-PD-1 독성을 재현; ***A. muciniphila* 농축으로 표지된 디스바이오시스**가 **Treg 취약성 + CD8⁺ 효과기 확장**을 유도(irColitis 환자에서도 관찰), 식이 되돌림·대사체 보충·Treg IFN-γ 차단으로 가역, 인체→마우스 FMT는 수용자 식이와 교호작용 (Patra et al., *Cell* 2026, DOI 10.1016/j.cell.2026.09.055, PMID 42913630). ⚠️ Akk는 **표지(marked by)** 로 기술 — 투여 개입 실험·균주/생균-살균 구분은 초록 범위 밖(확인 필요)
- [[Jay's Knowledge Base/raw/665-sagawa-2026-gut-microbiome-signatures-and-immune-checkpoint\|raw/665-sagawa-2026-gut-microbiome-signatures-and-immune-checkpoint]] — 소화기암에서 마이크로바이옴–ICI 시그니처의 **종양 유형·레지멘·인구 간 재현성과 번역 준비도(translational readiness)** 비판적 내러티브 리뷰: 인체 근거·실험 기전·종단 샘플링·임상 적용 기준 4축 평가 (*Current Oncology Reports* 2026, DOI 10.1007/s11912-026-01853-9). **초록 앞부분(목적·범위)만 확보 — 결론 미확보 · 모니터링**

## 관련 wiki 링크

- [[Jay's Knowledge Base/wiki/akkermansia-muciniphila\|akkermansia-muciniphila]]
- [[Jay's Knowledge Base/wiki/short-chain-fatty-acids\|short-chain-fatty-acids]]
- [[Jay's Knowledge Base/wiki/gut-microbiome-and-disease\|gut-microbiome-and-disease]]
- [[Jay's Knowledge Base/wiki/microbiome-therapeutics\|microbiome-therapeutics]]
- [[Jay's Knowledge Base/wiki/dysbiosis\|dysbiosis]]
- [[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]]
- [[Jay's Knowledge Base/wiki/gut-muscle-axis\|gut-muscle-axis]] — 암 악액질·골격근 소모의 미생물 축
- [[Jay's Knowledge Base/wiki/sarcopenia\|sarcopenia]] — 근소모 결과 지표의 공통 접점
- [[Jay's Knowledge Base/wiki/next-generation-probiotics\|next-generation-probiotics]] — *Phocaeicola vulgatus* 등 공생균 기반 후보
