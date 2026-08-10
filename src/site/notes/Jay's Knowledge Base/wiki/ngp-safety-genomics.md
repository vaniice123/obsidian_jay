---
{"dg-publish":true,"permalink":"/jay-s-knowledge-base/wiki/ngp-safety-genomics/","dg-note-properties":{}}
---

# NGP·LBP 균주의 게놈 기반 안전성 평가 (AMR·병독인자·HGT)

차세대 프로바이오틱스(NGP)·생균치료제(LBP) 후보 균주는 효능 형질만으로 선정되지 않는다. **획득 항생제내성(acquired antimicrobial resistance, AMR) 유전자, 병독인자(virulence factor, VF), 이동성 유전요소(mobile genetic element, MGE)** 세 가지를 게놈에서 찾아내고, 그것들이 **다른 균으로 전달될 수 있는가(transferability)** 를 판정하는 단계가 반드시 선행한다. 이 문서가 존재하는 이유는 Arlan et al. (2026)이 *Akkermansia*·*Faecalibacterium* 비교유전체 원저 17편을 PRISMA 2020 기준으로 종합하면서, 판게놈 구조와 기능 형질은 잘 정리된 반면 **AMR 유전자·병독/병원성 마커·수평유전자전달(horizontal gene transfer, HGT) 신호·위험지수(risk indices) 등 안전성 관련 유전체 특성은 연구 간 불균일하게 평가되었다**는 점을 핵심 연구 격차로 지목했기 때문이다 ([[Jay's Knowledge Base/raw/599-arlan-2026-comparative-genomic-insights-into-pangenome-diversity\|raw/599-arlan-2026-comparative-genomic-insights-into-pangenome-diversity]], Arlan et al. 2026, *F1000Research*). 즉 NGP 분야에는 **표준화된 게놈 기반 안전성 스크리닝**이 아직 확립되어 있지 않다. 이 문서는 그 스크리닝의 표적·방법·판정 논리를 균주 선별 관점에서 정리한다. 규제 제출 관점(어느 CTD 섹션에 무엇을 넣는가, QPS 등재 여부, 식약처/FDA/EMA 경로)은 [[Jay's Knowledge Base/wiki/lbp-regulatory-cmc\|lbp-regulatory-cmc]]가 담당하므로 여기서는 반복하지 않는다.

## 1. 무엇을 찾는가 — 스크리닝의 네 가지 표적

게놈 기반 안전성 평가는 서로 **독립적으로** 판정해야 하는 네 범주를 다룬다. Machado et al. (2022)이 *A. muciniphila* DSM 22959를 평가할 때 사용한 범주 구획이 실무 표준에 가깝다 ([[Jay's Knowledge Base/raw/103-machado-2022-insights-into-the-antimicrobial-resistance-prof\|raw/103-machado-2022-insights-into-the-antimicrobial-resistance-prof]], *Int. J. Environ. Res. Public Health*).

| 표적 | 찾는 것 | 판정에서의 역할 |
|---|---|---|
| **ARG** (antimicrobial resistance gene) | 내성 결정인자 서열 | 표현형 내성의 유전적 설명, 획득 여부 판단 |
| **VF** (virulence factor) | 독소·부착·침습 관련 유전자 | 병원성 잠재력 |
| **GI** (genomic island) | 수평 획득이 의심되는 게놈 구획 | 과거 HGT 흔적 |
| **MGE** (mobile genetic element) | 플라스미드·transposon·접합 요소 | **미래 전달 가능성** |

여기서 결정적인 것은 **ARG 목록과 MGE 목록이 별개**라는 점이다. 뒤의 §4에서 보듯 내성 유전자를 전혀 갖지 않은 요소가 다른 복제단위에 이동성을 부여할 수 있으므로, MGE는 ARG와 무관하게 독립 항목으로 스크리닝되어야 한다. Arlan 2026이 「AMR 유전자」와 「HGT 신호」를 나란히, 그러나 따로 열거한 것도 같은 이유다.

## 2. 어떻게 찾는가 — 표현형 시험과 in silico 스크리닝은 대체재가 아니다

**두 방법은 서로 다른 질문에 답한다.** 표현형 감수성 시험은 「이 균주가 실제로 이 약제에 견디는가」를, in silico 게놈 스크리닝은 「왜 견디며, 그 원인이 옮겨갈 수 있는가」를 답한다. 따라서 병행이 원칙이다.

- **표현형** — EFSA FEEDAP 가이던스는 국제 표준화된 방법으로 **최소억제농도(minimum inhibitory concentration, MIC)** 를 측정할 것을 요구하며, 기본 패널로 ampicillin, vancomycin, gentamicin, kanamycin, streptomycin, erythromycin, clindamycin, tetracycline, chloramphenicol을, 경우에 따라 tylosin, apramycin, nalidixic acid, sulfonamide, trimethoprim을 추가하도록 규정한다. 이 조합은 **가능한 한 넓은 범위의 내성 결정인자를 포착**하도록 선정된 것이다 ([[Jay's Knowledge Base/raw/107-unknown-guidance-on-the-assessment-of-bacterial-susceptibili\|raw/107-unknown-guidance-on-the-assessment-of-bacterial-susceptibili]], EFSA FEEDAP Panel, *EFSA Journal*; raw 파일에 연도 미기재, DOI 기준 2012).
- **in silico** — 게놈을 공개 데이터베이스·생물정보 도구로 스크리닝해 ARG·VF·GI·MGE를 동정한다 ([[Jay's Knowledge Base/raw/103-machado-2022-insights-into-the-antimicrobial-resistance-prof\|raw/103-machado-2022-insights-into-the-antimicrobial-resistance-prof]]).
- **교차 검증의 실제** — Machado et al.은 DSM 22959에 대해 broth microdilution과 E-test **두 표현형 방법이 동일한 범주 판정**을 냈고, gentamicin·kanamycin·streptomycin·ciprofloxacin에 대한 내성 표현형이 **게놈 맥락(genomic context)으로 뒷받침**됨을 확인했다. 결정적으로 동정된 ARG·VF에서 **수평 획득의 증거도, 전달 가능성도 발견되지 않았다**. 표현형 내성이 있으나 전달 위험은 없다는, 이 문서 §3의 전형적 판정 사례다.

절대혐기성·산소 극도 민감 균주에서는 표현형 시험 자체가 방법론적 난제가 된다(배양법·접종량 표준화). 이 실무 이슈는 [[Jay's Knowledge Base/wiki/lbp-regulatory-cmc\|lbp-regulatory-cmc]]에 정리되어 있다.

## 3. 판정의 핵심 — 내재적 내성 vs 획득·전달 가능 내성

**「내성이 있다」는 사실만으로는 탈락 사유가 되지 않는다.** 규제 판단을 가르는 것은 그 내성이 **종(species) 고유의 내재적(intrinsic) 형질인가, 외부에서 획득되어 다시 전달될 수 있는가**이다.

EFSA 가이던스의 판정 논리는 3단계로 읽힌다 ([[Jay's Knowledge Base/raw/107-unknown-guidance-on-the-assessment-of-bacterial-susceptibili\|raw/107-unknown-guidance-on-the-assessment-of-bacterial-susceptibili]]).

1. **cut-off 값 대조** — FEEDAP이 제시한 cut-off는 「획득 내성을 가진 균주」와 「감수성 균주」를 일관되게 분리하기 위한 **실용적(pragmatic) 기준**이며, 그 외의 용도로 쓰이도록 의도된 값이 아니다. 즉 임상적 breakpoint가 아니다.
2. **동일 분류군 내 비교** — 한 균주가 같은 분류학적 단위(taxonomic unit)의 다른 균주보다 특정 약제에 더 높은 내성을 보이면 **획득 내성이 시사**되며, 이때 내성의 **유전적 기반(genetic basis)에 대한 추가 정보가 요구**된다. 여기서 in silico 스크리닝이 필수 단계로 들어온다.
3. **탈락 판정** — 유전적 결정인자의 획득에 기인한 내성을 보유한 균주는 **수평 확산 잠재력이 가장 크므로 사용해서는 안 된다**고 명시되어 있다. 이것이 후보 탈락(kill criterion)의 문언적 근거다.

따라서 스크리닝 결과는 「ARG 몇 개 검출」이 아니라 **「검출된 결정인자가 내재적인가 / 이동성 요소에 실려 있는가 / 실제 전달 가능한가」** 라는 서술로 정리되어야 한다.

## 4. HGT 기전 자체 — *Bacteroides* 접합 요소 계보 (Shoemaker & Salyers)

전달 가능성 판정이 왜 게놈 목록만으로 끝나지 않는지는 1980~90년대 *Bacteroides* 유전학이 가장 명확히 보여준다. 아래 세 연구는 모두 *B. uniformis*를 재료로 삼았다(균주 자체의 프로필은 [[Jay's Knowledge Base/wiki/bacteroides-uniformis\|bacteroides-uniformis]] 참조).

- **염색체 → 이종(異種) 전달** — 접합성 *Bacteroides* 테트라사이클린 내성(Tc^r) 요소가 *B. uniformis* **염색체상의** IncP R751 유도체를 *E. coli* 수용균으로 옮기는 것을 **촉진(facilitate)** 한다 ([[Jay's Knowledge Base/raw/221-shoemaker-1987-facilitated-transfer-of-incpi-r751-derivative\|raw/221-shoemaker-1987-facilitated-transfer-of-incpi-r751-derivative]], Shoemaker & Salyers 1987, *J. Bacteriol.*; **초록 미확보** — 제목·서지만 확인). 문(phylum)을 가로지르는 전달이 가능하다는 점, 그리고 전달 능력이 **염색체 통합 요소에 의해 매개**된다는 점이 요지다.
- **항생제 노출이 방아쇠** — *B. uniformis* 0061을 tetracycline 1 µg/mL에 노출시키면 접합성 Tc^r 요소의 매개로 **NBU1(10.3 kb)·NBU2(11.5 kb) 플라스미드 유사 원형 DNA가 출현**한다. 이들은 평소 염색체에 통합되어 있다. 특기할 점은 **UV·thymidine 결핍·mitomycin C 같은 일반적 DNA 손상 자극으로는 유도되지 않았다**는 것 — 즉 SOS 반응이 아니라 **테트라사이클린이라는 특정 신호에 반응하는 조절 회로**다. 또한 다른 *Bacteroides* 종 3주에서 상동 서열이 검출되었다 ([[Jay's Knowledge Base/raw/222-shoemaker-1988-tetracycline-dependent-appearance-of-plasmidl\|raw/222-shoemaker-1988-tetracycline-dependent-appearance-of-plasmidl]], Shoemaker & Salyers 1988, *J. Bacteriol.*).
- **내성 유전자가 없어도 위험하다** — 65 kb 요소 **XBU4422**는 알려진 항생제 내성 유전자를 **전혀 갖지 않는(cryptic)** 염색체 통합 요소다. 그럼에도 이 요소가 삽입된 **비이동성(non-mobilizable) 벡터가 전달성(transmissible)을 획득**해 *Bacteroides*·*E. coli* 수용균으로 옮겨갔다. 삽입은 부위·방향 특이적이었고, 여섯 개 접합성 Tc^r 요소와 특히 말단부에서 상동성을 보였다 ([[Jay's Knowledge Base/raw/223-shoemaker-1990-a-cryptic-65-kilobase-pair-transposonlike-ele\|raw/223-shoemaker-1990-a-cryptic-65-kilobase-pair-transposonlike-ele]], Shoemaker & Salyers 1990, *J. Bacteriol.*).

**세 결과를 스크리닝 언어로 옮기면**: ① 전달 위험은 플라스미드에 국한되지 않고 **염색체 통합 요소에서도 발생**한다, ② 위험은 상시적이 아니라 **선택압(항생제 노출) 조건부로 발현**되므로 정상 배양 조건의 관찰만으로는 배제할 수 없다, ③ **ARG를 갖지 않은 MGE도 mobilization 능력을 부여**하므로 「내성 유전자 목록이 깨끗하다」는 것이 「HGT 위험이 없다」와 동의어가 아니다. §1에서 MGE를 ARG와 독립 항목으로 둔 이유가 여기 있다.

> **이 근거가 확립하는 것과 하지 않는 것.** 위 연구들은 Southern 혼성화·제한효소 지도·접합 실험에 기반한 1980~90년대 작업으로, 실험실 균주(*B. uniformis* 0061)와 선택 조건 하 in vitro mating을 사용했다. 따라서 **기전적 가능성(mechanistic plausibility)** 과 *Bacteroides* 계통에서의 요소 분포는 확립하지만, **현대 NGP 후보에서의 전달 빈도(frequency)나 생체 내(in vivo) 장내 발생률은 정량하지 않는다**. 특히 *Akkermansia*(Verrucomicrobiota)·*Faecalibacterium*(Bacillota)은 *Bacteroides*와 접합 기구가 다르므로 직접 외삽할 수 없다. 실제로 Machado et al.의 *A. muciniphila* DSM 22959 평가에서는 전달 가능성 증거가 나오지 않았다. 이 계보의 가치는 **「무엇을 배제해야 하는지」의 목록을 정의**하는 데 있지, 위험이 높다는 결론을 대신하는 데 있지 않다.
>
> 서지 주의: [[Jay's Knowledge Base/raw/226-shoemaker-chromosome-of-bacteroides-uniformis-to-escherichia\|raw/226-shoemaker-chromosome-of-bacteroides-uniformis-to-escherichia]]는 제목이 절단된 채 연도·저널 정보가 없고 **초록 미확보** 상태로, 위 1987년 논문(raw/221)의 중복 레코드로 보인다. 독립 근거로 계수하지 않았다.

## 5. 판정 프레임워크 — EFSA QPS와 그 한계

**QPS(Qualified Presumption of Safety)** 는 식품·사료에 의도적으로 첨가되는 생물학적 제제에 대한 **분류학적 단위(taxonomic unit, TU) 단위의 일반 안전성 평가** 체계로, ① 분류학적 동일성, ② 지식 체계(body of knowledge), ③ 안전성 우려, ④ **항균제 내성** 네 축을 평가한다. TU 수준에서 확인된 우려는 가능한 한 **균주 또는 제품 수준에서 확인**하도록 「qualification」으로 반영된다 ([[Jay's Knowledge Base/raw/36-unknown-2020-update-of-the-list-of-qpsrecommended-biological\|raw/36-unknown-2020-update-of-the-list-of-qpsrecommended-biological]], EFSA BIOHAZ Panel 2020, *EFSA Journal*). 2019년 4~9월 통보된 54건 처리 결과가 이 체계의 작동 방식을 보여준다 — 23건은 이미 QPS 보유, 14건 제외, 16개 TU에 해당하는 17건을 평가해 8개 TU를 권고했고, 권고에는 「생산 목적에 한함」·「독소생성능 부재」 같은 조건이 붙었다. 권고 불가 사유는 대부분 **지식 체계 부족** 또는 안전성 우려였다.

미생물의 특성분석 자체에 대한 요구사항은 별도 FEEDAP 가이던스가 규율한다 ([[Jay's Knowledge Base/raw/106-unknown-guidance-on-the-characterisation-of-microorganisms-u\|raw/106-unknown-guidance-on-the-characterisation-of-microorganisms-u]], *EFSA Journal*; raw 파일 연도 미기재, DOI 기준 2018 — **초록이 적용범위 서술에 그쳐 세부 요구항목은 원문 확인 필요**).

**NGP 관점에서의 함의는 명확하다.** *Akkermansia*·*Faecalibacterium*처럼 QPS 목록에 없는 분류군은 「지식 체계 부족」 범주에 놓이며, 따라서 **일반 안전성 추정을 빌려올 수 없고 균주 수준 입증이 전부**가 된다 (규제 경로 상세는 [[Jay's Knowledge Base/wiki/lbp-regulatory-cmc\|lbp-regulatory-cmc]], 후보 균주 라인업은 [[Jay's Knowledge Base/wiki/next-generation-probiotics\|next-generation-probiotics]]).

## 6. 균주 수준 데이터 패키지의 실제 — 참조 사례

- ***E. faecium* B13 (발효 고추 유래)** — 기회감염 병원체 속에 속하는 균주를 후보로 밀고 나가려면 어떤 데이터가 필요한지 보여주는 사례다 ([[Jay's Knowledge Base/raw/230-xiao-2024-assessment-of-the-safety-and-probiotic-properties\|raw/230-xiao-2024-assessment-of-the-safety-and-probiotic-properties]], Xiao et al. 2024, *Microorganisms*). 게놈은 염색체 1개 + **플라스미드 2개**(→ MGE 항목의 1차 관심사)로 구성되며, ANI 기준 임상 계통이 아닌 **발효식물 유래 균주에 근연**함이 확인되었다. **임상 *E. faecium*의 주요 병독 유전자는 보유하지 않았고**, 내성 유전자로 `aac(6′)-Ii`·`ant(6)-Ia`·`msrC`가 검출되었다. 표현형에서는 12종 항생제에 감수성, erythromycin·rifampicin·tetracycline·doxycycline·minocycline에 내성이었다. 여기에 용혈성 부재, gelatinase·ornithine/lysine decarboxylase·tryptophanase 활성 부재 같은 **생화학적 병독 표지 음성**, 그리고 28일 투여 후 장내 α-다양성 불변·병독 유전자 증가 없음이라는 in vivo 확인이 더해진다.
  - **읽는 법 두 가지.** ① 초록은 검출된 세 유전자의 **내재/획득 구분과 전달 가능성 판정을 명시하지 않는다** — §3 기준으로는 바로 그 구분이 결론을 좌우하는 지점이므로, 이 패키지는 「유전자 검출」까지는 모범적이나 「전달 가능성 판정」에서 서술이 얇다. ② tetracycline·doxycycline·minocycline **내성 표현형에 대응하는 내성 유전자가 보고 목록에 없다** — 게놈–표현형 불일치는 흔한 결과이며, 이 때문에 §2의 병행 원칙이 필요하다.
- **속(genus) 차원의 기저율** — 한국 유통 가공 돈육 제품 분리 *E. faecium* 30주에서 erythromycin 80%, clindamycin 50%, nitrofurantoin 20% 내성이 관찰되었고 반코마이신 내성균은 없었다 ([[Jay's Knowledge Base/raw/229-kim-2020-occurrence-antimicrobial-resistance-and-molecular-d\|raw/229-kim-2020-occurrence-antimicrobial-resistance-and-molecular-d]], Kim & Koo 2020, *Foods*). 식품 유래 분리주에서도 획득 내성 빈도가 상당하다는 뜻으로, **분리원이 「식품」이라는 사실이 안전성 논거가 되지 못함**을 보여준다.
- **재배열 잠재력** — *E. faecium*·*E. casseliflavus* 종군에 **ccrABEnt serine recombinase 유전자가 광범위하게 분포하며 *E. faecium*에서 발현**된다 ([[Jay's Knowledge Base/raw/233-bjørkeng-2010-ccrabent-serine-recombinase-genes-are-widely-d\|raw/233-bjørkeng-2010-ccrabent-serine-recombinase-genes-are-widely-d]], Bjørkeng et al. 2010, *Microbiology*; **초록 미확보** — 제목·서지 기준). 부위특이적 재조합효소의 상재는 §4의 XBU4422와 같은 결의 문제, 즉 **ARG와 별개로 게놈 재배열·요소 이동의 기구가 갖춰져 있는가**를 묻게 한다.

## 7. 한계와 미해결

- **표준 부재가 최대 공백.** Arlan 2026의 지적대로 안전성 유전체 지표는 연구마다 다르게 평가된다. 어떤 데이터베이스·어떤 동일성 임계값·어떤 「위험지수」를 쓸지에 대한 분야 합의가 없어, **연구 간 비교가 성립하지 않는다** ([[Jay's Knowledge Base/raw/599-arlan-2026-comparative-genomic-insights-into-pangenome-diversity\|raw/599-arlan-2026-comparative-genomic-insights-into-pangenome-diversity]]).
- **개방형 판게놈이 문제를 키운다.** *Akkermansia*·*Faecalibacterium* 모두 대규모 부속유전체를 가지므로, **한 균주의 안전성 결론을 같은 종의 다른 균주로 옮길 수 없다**. 균주별 재평가가 원칙이다 ([[Jay's Knowledge Base/wiki/akkermansia-strain-landscape\|akkermansia-strain-landscape]]·[[Jay's Knowledge Base/wiki/faecalibacterium-prausnitzii\|faecalibacterium-prausnitzii]]).
- **음성 결과의 해석 한계.** 「전달 가능성 증거 없음」은 현재 데이터베이스에 등재된 결정인자에 한한 진술이다. 신규·미기재 요소는 원리상 검출되지 않는다.
- **표현형–유전형 불일치의 처리 규칙 부재.** §6의 B13 사례처럼 설명되지 않는 내성 표현형이 남았을 때 어떻게 판정할지에 대한 공통 규칙이 없다.
- **기전 근거의 노후.** HGT 기전의 1차 근거는 여전히 1980~90년대 *Bacteroides* 유전학에 크게 의존하며, 현대 NGP 분류군에서 동등한 해상도의 접합·mobilization 실험은 드물다.
- **생균 외 제형.** 살균·불활성화 제제의 잔존 DNA에 전이성 내성 유전자가 포함될 가능성도 평가 범위에 들어간다 — 이 논점은 [[Jay's Knowledge Base/wiki/lbp-regulatory-cmc\|lbp-regulatory-cmc]]와 [[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]]에 정리되어 있다.

## 관련 문서
[[Jay's Knowledge Base/wiki/lbp-regulatory-cmc\|lbp-regulatory-cmc]] · [[Jay's Knowledge Base/wiki/next-generation-probiotics\|next-generation-probiotics]] · [[Jay's Knowledge Base/wiki/akkermansia-strain-landscape\|akkermansia-strain-landscape]] · [[Jay's Knowledge Base/wiki/faecalibacterium-prausnitzii\|faecalibacterium-prausnitzii]] · [[Jay's Knowledge Base/wiki/bacteroides-uniformis\|bacteroides-uniformis]] · [[Jay's Knowledge Base/wiki/akkermansia-muciniphila\|akkermansia-muciniphila]] · [[Jay's Knowledge Base/wiki/probiotics-prebiotics-postbiotics\|probiotics-prebiotics-postbiotics]] · [[Jay's Knowledge Base/wiki/microbiome-analysis-technologies\|microbiome-analysis-technologies]]

## 출처
- [[Jay's Knowledge Base/raw/599-arlan-2026-comparative-genomic-insights-into-pangenome-diversity\|raw/599-arlan-2026-comparative-genomic-insights-into-pangenome-diversity]] — *Akkermansia*·*Faecalibacterium* 비교유전체 체계적 문헌고찰(PRISMA 2020, 167건→17건). 안전성 유전체 지표(AMR 유전자·병독/병원성 마커·HGT 신호·위험지수)가 연구 간 불균일하게 평가되었다는 격차 지적 — 본 문서의 출발점 (*F1000Research* 2026)
- [[Jay's Knowledge Base/raw/103-machado-2022-insights-into-the-antimicrobial-resistance-prof\|raw/103-machado-2022-insights-into-the-antimicrobial-resistance-prof]] — *A. muciniphila* DSM 22959의 표현형(broth microdilution·E-test, 8종) + in silico(ARG·VF·GI·MGE) 병행 평가. gentamicin·kanamycin·streptomycin·ciprofloxacin 내성이 게놈 맥락과 일치, 수평 획득·전달 가능성 증거 없음 (*Int. J. Environ. Res. Public Health* 2022)
- [[Jay's Knowledge Base/raw/107-unknown-guidance-on-the-assessment-of-bacterial-susceptibili\|raw/107-unknown-guidance-on-the-assessment-of-bacterial-susceptibili]] — EFSA FEEDAP 항균제 감수성 평가 가이던스. MIC 필수 패널 규정, cut-off로 획득 내성/감수성 분리, 획득 결정인자 기인 내성 균주는 수평 확산 잠재력 최대이므로 사용 불가 (*EFSA Journal*; raw 연도 미기재, DOI 기준 2012)
- [[Jay's Knowledge Base/raw/106-unknown-guidance-on-the-characterisation-of-microorganisms-u\|raw/106-unknown-guidance-on-the-characterisation-of-microorganisms-u]] — EFSA FEEDAP 미생물 특성분석 가이던스. Regulation (EC) No 1831/2003 제7.6조 신청서 작성 지침 (*EFSA Journal*; raw 연도 미기재, DOI 기준 2018 — **초록이 적용범위 서술에 그침**, 세부 요구항목 원문 확인 필요)
- [[Jay's Knowledge Base/raw/36-unknown-2020-update-of-the-list-of-qpsrecommended-biological\|raw/36-unknown-2020-update-of-the-list-of-qpsrecommended-biological]] — EFSA QPS 11차 업데이트. 분류학적 동일성·지식 체계·안전성 우려·항균제 내성 4축 평가, TU 단위 판정 + 균주/제품 수준 qualification, 2019년 통보 54건 처리 내역 (*EFSA Journal* 2020)
- [[Jay's Knowledge Base/raw/230-xiao-2024-assessment-of-the-safety-and-probiotic-properties\|raw/230-xiao-2024-assessment-of-the-safety-and-probiotic-properties]] — *E. faecium* B13의 게놈+표현형+in vivo 안전성 데이터 패키지. 염색체 1 + 플라스미드 2, 임상 주요 병독 유전자 부재, `aac(6′)-Ii`/`ant(6)-Ia`/`msrC` 보유, 12종 감수성·5종 내성, 28일 투여 후 이상 없음 (*Microorganisms* 2024)
- [[Jay's Knowledge Base/raw/221-shoemaker-1987-facilitated-transfer-of-incpi-r751-derivative\|raw/221-shoemaker-1987-facilitated-transfer-of-incpi-r751-derivative]] — 접합성 *Bacteroides* Tc^r 요소가 *B. uniformis* **염색체상** IncP R751 유도체의 *E. coli*로의 전달을 촉진 (*J. Bacteriol.* 1987; **초록 미확보**, 제목·서지 기준)
- [[Jay's Knowledge Base/raw/222-shoemaker-1988-tetracycline-dependent-appearance-of-plasmidl\|raw/222-shoemaker-1988-tetracycline-dependent-appearance-of-plasmidl]] — tetracycline 노출 시 접합성 Tc^r 요소 매개로 NBU1(10.3 kb)·NBU2(11.5 kb) 플라스미드 유사형 출현; 평소 염색체 통합 상태, UV·mitomycin C 등으로는 유도되지 않음, 타 *Bacteroides* 종에 상동 서열 (*J. Bacteriol.* 1988)
- [[Jay's Knowledge Base/raw/223-shoemaker-1990-a-cryptic-65-kilobase-pair-transposonlike-ele\|raw/223-shoemaker-1990-a-cryptic-65-kilobase-pair-transposonlike-ele]] — 내성 유전자를 갖지 않는 65 kb cryptic 요소 XBU4422가 비이동성 벡터에 전달성을 부여, 부위·방향 특이적 삽입, 접합성 Tc^r 요소 6종과 말단 상동성 — **ARG 부재 ≠ HGT 위험 부재**의 직접 근거 (*J. Bacteriol.* 1990)
- [[Jay's Knowledge Base/raw/226-shoemaker-chromosome-of-bacteroides-uniformis-to-escherichia\|raw/226-shoemaker-chromosome-of-bacteroides-uniformis-to-escherichia]] — 제목 절단·연도/저널 미상·**초록 미확보**. raw/221(1987)의 중복 레코드로 판단되어 독립 근거로 사용하지 않음
- [[Jay's Knowledge Base/raw/229-kim-2020-occurrence-antimicrobial-resistance-and-molecular-d\|raw/229-kim-2020-occurrence-antimicrobial-resistance-and-molecular-d]] — 한국 가공 돈육 제품 분리 *E. faecium* 30주의 14종 항균제 내성(erythromycin 80%·clindamycin 50%·nitrofurantoin 20%, VRE 없음)과 rep-PCR 분자다양성 — 식품 유래 분리주의 획득 내성 기저율 (*Foods* 2020)
- [[Jay's Knowledge Base/raw/233-bjørkeng-2010-ccrabent-serine-recombinase-genes-are-widely-d\|raw/233-bjørkeng-2010-ccrabent-serine-recombinase-genes-are-widely-d]] — *E. faecium*·*E. casseliflavus* 종군에 ccrABEnt serine recombinase 유전자 광범위 분포·*E. faecium*에서 발현 (*Microbiology* 2010; **초록 미확보**, 제목·서지 기준)
