---
{"dg-publish":true,"permalink":"/jay-s-knowledge-base/wiki/bile-acid-metabolism/","dg-note-properties":{}}
---

# 담즙산 대사(Bile Acid Metabolism)와 장내 미생물

담즙산(bile acid)은 지방 유화를 위한 계면활성 분자에 그치지 않고, **숙주 수용체에 결합하는 신호 분자(signalling molecule)** 로 기능한다. 장내 미생물은 숙주가 만든 1차 담즙산을 화학적으로 변형시켜 담즙산 풀(pool)의 조성을 바꾸고, 바뀐 조성은 핵수용체 **FXR**과 막수용체 **TGR5**를 통해 지질 흡수·간 대사·골격근 항상성·에너지 대사로 번역된다. 즉 담즙산은 **미생물의 효소 활성이 숙주 생리로 전환되는 공용 통로**이며, 이 문서는 여러 주제 문서에 흩어져 있던 그 통로를 한곳에 정리한다. SCFA가 「발효 산물이 수용체를 자극하는」 경로라면, 담즙산은 「숙주 분자를 미생물이 개조해 되돌려주는」 경로라는 점에서 대비된다 (cf. [[Jay's Knowledge Base/wiki/short-chain-fatty-acids\|short-chain-fatty-acids]]).

## 1. 담즙산 풀의 기본 구조

> 이 절은 교과서적 배경이며 특정 원저에 귀속되지 않는다. 이후 절의 원저 근거를 읽기 위한 최소 전제만 정리한다.

- **1차 담즙산(primary BA)**: 간에서 콜레스테롤로부터 합성. 대표적으로 **콜산(cholic acid, CA)**, **케노데옥시콜산(chenodeoxycholic acid, CDCA)**.
- **포합(conjugation)**: 간에서 글리신·타우린이 결합된 형태로 담즙에 분비된다. 포합형은 수용성이 높아 장에서 흡수·확산이 제한된다.
- **장간순환(enterohepatic circulation)**: 분비된 담즙산의 대부분이 회장(ileum)에서 재흡수되어 간으로 돌아간다. 따라서 **회장은 담즙산 신호가 집중되는 해부학적 요충지**다.
- **2차 담즙산(secondary BA)**: 대장에서 미생물 변환을 거친 산물.

## 2. 미생물의 두 가지 핵심 변환

담즙산 풀을 바꾸는 미생물 효소 활성은 크게 둘로 나뉘며, **어느 쪽을 가진 균주인가가 곧 그 균주의 작용 기전**이 된다.

### 2.1 탈포합 — 담즙염 가수분해효소(BSH)
**BSH(bile salt hydrolase)** 는 포합형 담즙산에서 글리신·타우린을 떼어내 유리(unconjugated) 담즙산으로 만든다. 이는 후속 변환의 관문이자, FXR에 대한 리간드 성질을 바꾸는 단계다.

실무적으로 중요한 점은 **BSH 활성이 측정 가능한 분자 지표**라는 것이다. Hua et al. (2026)은 BSH 고활성 균주를 선별 기준으로 삼아 *Lactiplantibacillus plantarum* H-87, *Bifidobacterium animalis* F1-7·F1-3-2를 골라냈고, 그중 F1-7·F1-3-2가 실제 근감소 모델에서 효능을 보였다 — 즉 **효소 활성 스크리닝 → 표현형 효능**이 연결된 사례다 ([[Jay's Knowledge Base/raw/602-hua-2026-bile-salt-hydrolase-active-bifidobacterium-animalis\|raw/602-hua-2026-bile-salt-hydrolase-active-bifidobacterium-animalis]], *Food Chemistry*).

### 2.2 7α-탈수산화 — 2차 담즙산 생성
일부 장내 세균은 유리 담즙산을 **2차 담즙산으로 전환**한다. ***Clostridium scindens*** 가 대표적인 담즙산 전환균으로, 고지방식 조건에서 확장하며 담즙산 조성을 재편하는 것이 확인되었다 ([[Jay's Knowledge Base/raw/574-liang-2026-dietary-fat-alters-goblet-cell-function-and-microbial\|raw/574-liang-2026-dietary-fat-alters-goblet-cell-function-and-microbial]], Liang et al. 2026, *Nature Microbiology*).

이 방향의 산물이 항상 유익한 것은 아니다. 살균 *A. muciniphila* MucT를 보충한 개 모델에서는 **미생물 유래 2차 담즙산과 oxo-유도체(대사 이상과 연관되는 분획)가 감소**하며 담즙산 프로파일이 정상화되었다 ([[Jay's Knowledge Base/raw/589-timmerman-2026-pasteurized-akkermansia-muciniphila-muct-reduces-high\|raw/589-timmerman-2026-pasteurized-akkermansia-muciniphila-muct-reduces-high]], Timmerman et al. 2026, *Microbiology Spectrum*). 즉 **2차 담즙산 과잉은 교정 대상**일 수 있다.

## 3. 수용체 — 담즙산이 신호가 되는 지점

| 수용체 | 유형 | 국재 | 하류 |
|---|---|---|---|
| **FXR** (farnesoid X receptor) | 핵수용체(nuclear receptor) | 회장 상피, 간 | FGF15/19 분비, 지질 흡수 유전자 |
| **TGR5** (Takeda G protein-coupled receptor 5) | 막수용체(GPCR) | 간, 대사 조직 | AMPK 경유 당·지질 대사 |

**FXR**은 담즙산을 리간드로 삼아, 미생물이 바꾼 담즙산 조성을 **곧바로 숙주 유전자 발현으로 번역**한다. **TGR5**는 별개의 막수용체 축으로, *Bacteroides uniformis*가 촉진한 CA·CDCA가 **TGR5/AMPK 경로**를 통해 간의 당신생·지질분해를 억제해 당뇨 모델의 당·지질 대사를 개선했으며, **TGR5를 knockdown하면 그 이득이 사라졌다** ([[Jay's Knowledge Base/raw/224-zhu-2024-bacteroides-uniformis-ameliorates-carbohydrate-and\|raw/224-zhu-2024-bacteroides-uniformis-ameliorates-carbohydrate-and]], Zhu et al. 2024, *Pharmaceuticals*). 수용체 결손으로 인과를 확인한 사례라는 점에서 근거 강도가 높다.

## 4. 하류 갈래 — 같은 신호, 세 갈래 결과

### 4.1 장 → 근육 (내분비 갈래)
회장 FXR 활성화는 **FGF15**(설치류)/**FGF19**(사람 상동체)의 분비를 유도한다. 이 인자는 **혈류를 타고 원격 조직에 작용하는 내분비 인자**이며, 골격근에서는 수용체 **FGFR4**가 보조수용체 **KLB(β-Klotho)** 와 복합체를 이룰 때 신호가 전달되어 **근단백 분해가 억제**된다. BSH 고활성 균주가 덱사메타손 유도 근감소 모델에서 근육량·근섬유 단면적·운동수행능력을 개선한 것이 이 경로의 근거다 ([[Jay's Knowledge Base/raw/602-hua-2026-bile-salt-hydrolase-active-bifidobacterium-animalis\|raw/602-hua-2026-bile-salt-hydrolase-active-bifidobacterium-animalis]]).

이 「장에서 분비 → 순환 → 근육에서 수신」 구조가, 국소 확산에 의존하는 SCFA 경로와 구별되는 **내분비 경로**로서의 성격을 만든다. 상세 → [[Jay's Knowledge Base/wiki/gut-muscle-axis\|gut-muscle-axis]]

### 4.2 장 → 소장 지질 흡수 (국소 갈래)
같은 FXR이 소장에서는 **지방 흡수를 촉진하는** 방향으로 작동한다. 변형된 담즙산 풀이 소장에서 **FXR–PLIN2 신호를 활성화**하고 장세포 **PPARα 의존 흡수 경로를 상향**시켜 지방 흡수가 증가한다 ([[Jay's Knowledge Base/raw/574-liang-2026-dietary-fat-alters-goblet-cell-function-and-microbial\|raw/574-liang-2026-dietary-fat-alters-goblet-cell-function-and-microbial]]; 논평 [[Jay's Knowledge Base/raw/572-holmberg-2026-fatty-diets-disrupt-mucusmicrobiomemetabolite\|raw/572-holmberg-2026-fatty-diets-disrupt-mucusmicrobiomemetabolite]]).

- **PLIN2**(perilipin-2): **지질방울(lipid droplet) 피막 단백질** — 흡수된 지방을 장세포 안에 축적·보관하는 실행 단계.
- **PPARα**: 지질 대사 전사인자이나, **이 맥락에서는 통상 알려진 지방산 산화가 아니라 장세포의 지질 흡수 상향**으로 작동한다. 배경지식이 있을수록 오해하기 쉬운 지점이므로 주의.

### 4.3 장 → 간 (gut–liver axis)
TGR5/AMPK 경유로 간의 당신생·지질분해가 조절된다([[Jay's Knowledge Base/raw/224-zhu-2024-bacteroides-uniformis-ameliorates-carbohydrate-and\|raw/224-zhu-2024-bacteroides-uniformis-ameliorates-carbohydrate-and]]). 상세 → [[Jay's Knowledge Base/wiki/bacteroides-uniformis\|bacteroides-uniformis]]

## 5. 점액층과의 결합 — 담즙산 축의 상류

담즙산 축은 독립적으로 작동하지 않고 **점액층 상태에 종속**된다. 고지방식이 배상세포(goblet cell)의 글루타민 대사·산화환원 항상성을 손상시켜 점액층이 얇아지면, 점액 적응 공생균 ***A. muciniphila*가 고갈**되고 담즙산 전환균 ***C. scindens*가 확장**한다. 그 결과 담즙산 조성이 바뀌어 소장 지방 흡수가 증가한다. 결정적으로 **글루타민 보충이 배상세포 기능과 담즙산 풀을 회복시켜 FXR 활성과 지질 흡수를 낮췄다** — 이 축이 되돌릴 수 있는 중재점임을 뜻한다 ([[Jay's Knowledge Base/raw/574-liang-2026-dietary-fat-alters-goblet-cell-function-and-microbial\|raw/574-liang-2026-dietary-fat-alters-goblet-cell-function-and-microbial]]).

즉 **점액 niche 교란 → 미생물 조성 변화 → 담즙산 재편 → 원격 대사 변화**라는 연쇄이며, 대장의 점액 사건이 소장의 지질 흡수를 원격 조절한다는 점이 이 발견의 핵심이다. 점액층 자체는 [[Jay's Knowledge Base/wiki/akkermansia-mechanisms\|akkermansia-mechanisms]] 및 [[Jay's Knowledge Base/wiki/dysbiosis\|dysbiosis]] 참조.

## 6. 중재 관점에서의 함의

1. **BSH 활성 = 균주 선별 지표**. 효능 기전이 곧 측정 가능한 효소 활성이므로, 후보 균주 스크리닝에 정량 지표를 제공한다 ([[Jay's Knowledge Base/raw/602-hua-2026-bile-salt-hydrolase-active-bifidobacterium-animalis\|raw/602-hua-2026-bile-salt-hydrolase-active-bifidobacterium-animalis]]). 이는 「어떤 균주를 왜 골랐는가」를 설명해야 하는 개발 단계에서 유리하다 (cf. [[Jay's Knowledge Base/wiki/next-generation-probiotics\|next-generation-probiotics]]).
2. **살균 제제도 담즙산 축을 움직인다**. 살균 *A. muciniphila* MucT가 담즙산 프로파일을 정상화시킨 결과는, 생균 정착 없이도 이 축에 개입할 수 있음을 시사한다 ([[Jay's Knowledge Base/raw/589-timmerman-2026-pasteurized-akkermansia-muciniphila-muct-reduces-high\|raw/589-timmerman-2026-pasteurized-akkermansia-muciniphila-muct-reduces-high]]). 「살균 vs 생균」 논의와 접점 → [[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]]
3. **약물–미생물 상호작용의 경유지**. 당뇨병 치료제가 장내 미생물에 미치는 영향의 기전 후보 중 하나로 **담즙산 대사 조절**이 거론된다 ([[Jay's Knowledge Base/raw/48-chaithanya-2024-metabolic-consequences-of-alterations-in-gut\|raw/48-chaithanya-2024-metabolic-consequences-of-alterations-in-gut]], Chaithanya et al. 2024). 다만 이 문헌은 종설이며 기전이 확정된 것은 아니다.

## 7. 주의할 점 · 미해결

- **FXR의 방향성이 조직마다 다르다.** 회장에서는 FGF15/19를 통해 근단백 보존 쪽으로, 소장에서는 지질 흡수 증가 쪽으로 작동한다. **「FXR 활성화 = 좋다/나쁘다」로 단순화할 수 없으며**, 어느 조직·어느 하류를 보는지 반드시 명시해야 한다.
- **2차 담즙산의 양면성.** *B. uniformis* 사례에서는 CA·CDCA 증가가 이로웠고([[Jay's Knowledge Base/raw/224-zhu-2024-bacteroides-uniformis-ameliorates-carbohydrate-and\|raw/224-zhu-2024-bacteroides-uniformis-ameliorates-carbohydrate-and]]), 개 모델에서는 2차 담즙산·oxo-유도체 감소가 이로웠다([[Jay's Knowledge Base/raw/589-timmerman-2026-pasteurized-akkermansia-muciniphila-muct-reduces-high\|raw/589-timmerman-2026-pasteurized-akkermansia-muciniphila-muct-reduces-high]]). **어떤 분획이 어느 방향으로 움직이는가**가 관건이며, 총량 논의는 의미가 약하다.
- **종간 차이.** FGF15(설치류)와 FGF19(사람)는 상동체이나 동일하지 않다. 근거의 다수가 마우스·개 모델이므로 인체 외삽에는 단서가 필요하다.
- **인체 데이터 공백.** 위 근거는 전임상 중심이며, BSH 활성 균주의 인체 근감소·대사 종결점 RCT는 확인되지 않았다.

## 관련 문서
[[Jay's Knowledge Base/wiki/gut-muscle-axis\|gut-muscle-axis]] · [[Jay's Knowledge Base/wiki/obesity-body-composition\|obesity-body-composition]] · [[Jay's Knowledge Base/wiki/akkermansia-mechanisms\|akkermansia-mechanisms]] · [[Jay's Knowledge Base/wiki/bacteroides-uniformis\|bacteroides-uniformis]] · [[Jay's Knowledge Base/wiki/short-chain-fatty-acids\|short-chain-fatty-acids]] · [[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]] · [[Jay's Knowledge Base/wiki/next-generation-probiotics\|next-generation-probiotics]] · [[Jay's Knowledge Base/wiki/dysbiosis\|dysbiosis]]

## 출처
- [[Jay's Knowledge Base/raw/602-hua-2026-bile-salt-hydrolase-active-bifidobacterium-animalis\|raw/602-hua-2026-bile-salt-hydrolase-active-bifidobacterium-animalis]] — BSH 고활성 *B. animalis* F1-7·F1-3-2의 담즙산 탈포합→회장 FXR–FGF15→근육 FGFR4/KLB 경유 근감소 완화, 발효유 적용 (*Food Chemistry* 2026)
- [[Jay's Knowledge Base/raw/574-liang-2026-dietary-fat-alters-goblet-cell-function-and-microbial\|raw/574-liang-2026-dietary-fat-alters-goblet-cell-function-and-microbial]] — 고지방식→배상세포 글루타민대사·산화환원 손상→점액층 박화→*A. muciniphila* 고갈·*C. scindens* 확장→담즙산 FXR-PLIN2/PPARα→소장 지방흡수↑, 글루타민 rescue (*Nature Microbiology* 2026)
- [[Jay's Knowledge Base/raw/572-holmberg-2026-fatty-diets-disrupt-mucusmicrobiomemetabolite\|raw/572-holmberg-2026-fatty-diets-disrupt-mucusmicrobiomemetabolite]] — 위 원저의 News & Views 해설 (*Nature Microbiology* 2026)
- [[Jay's Knowledge Base/raw/224-zhu-2024-bacteroides-uniformis-ameliorates-carbohydrate-and\|raw/224-zhu-2024-bacteroides-uniformis-ameliorates-carbohydrate-and]] — *B. uniformis*가 CA·CDCA 생산 촉진→TGR5/AMPK 경유 간 당신생·지질분해 억제로 T2DM 개선, TGR5 knockdown 시 소실 (*Pharmaceuticals* 2024)
- [[Jay's Knowledge Base/raw/589-timmerman-2026-pasteurized-akkermansia-muciniphila-muct-reduces-high\|raw/589-timmerman-2026-pasteurized-akkermansia-muciniphila-muct-reduces-high]] — 살균 *A. muciniphila* MucT가 고열량식 개 모델서 체중 증가 억제·염증 감소·담즙산 프로파일 정상화(2차 담즙산·oxo-유도체 감소) (*Microbiology Spectrum* 2026)
- [[Jay's Knowledge Base/raw/48-chaithanya-2024-metabolic-consequences-of-alterations-in-gut\|raw/48-chaithanya-2024-metabolic-consequences-of-alterations-in-gut]] — 당뇨병 치료제–장내 미생물 상호작용 종설, 기전 후보로 담즙산 대사 조절 거론 (*Diabetes Epidemiology and Management* 2024)
