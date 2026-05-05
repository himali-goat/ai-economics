# Value chain analysis — extended notes

## Where value concentrates

The AI CapEx value chain is not a uniform pipeline — value pools are highly asymmetric across the five layers.

**Layer 1 (Hyperscalers):** Enormous value creation but through application and platform, not infrastructure. CapEx is a cost to them, not a revenue driver directly. The spend is a strategic moat — competitors cannot match it quickly.

**Layer 5 (Silicon):** NVDA captures outsized margin (~75% gross margin on data center GPUs). TSM commands pricing power at leading nodes (3nm, 2nm) because there is no credible alternative at scale. LRCX and the broader WFE (wafer fab equipment) cluster benefit from every new fab build.

**Layers 2–4 (MEP, Compute fabric, Networking):** More competitive, lower margin. EME, FIX are construction-adjacent businesses. CLS/STX are volume businesses. MRVL is the interesting exception — custom silicon design moves it up the value chain.

---

## Bottleneck analysis (architect lens)

The physical constraints that could delay a data center build, ordered by current risk:

1. **Grid power** — Long-lead utility interconnects (18–36 months) are the dominant constraint for new campuses in 2024–2025. PWR and the utilities themselves are the choke point.
2. **Cooling infrastructure** — Liquid cooling deployment (VRT, FIX) requires building redesigns; not all existing facilities can retrofit.
3. **HBM supply (MU + SK Hynix + Samsung)** — NVDA GPU shipments have been constrained by HBM availability, not by TSMC capacity alone.
4. **Advanced packaging** — CoWoS (Chip on Wafer on Substrate) capacity at TSMC is a secondary bottleneck specific to NVDA H100/H200.
5. **Skilled MEP labor** — Electricians and mechanical contractors qualified for data center work are in short supply regionally.

---

## Competitive dynamics by layer

### Layer 1 — Hyperscaler CapEx race
The four major hyperscalers are in an arms race. Microsoft (Azure + OpenAI), Google (GCP + DeepMind), Amazon (AWS + Trainium), and Meta (Llama + internal AI) cannot afford to fall behind on infrastructure because AI model quality correlates with compute at training time. This creates a multi-year committed CapEx tailwind for all downstream layers.

### Layer 5 — Semiconductor concentration risk
- NVDA holds ~80%+ share of AI training accelerators
- TSM manufactures virtually all leading-edge AI chips (NVDA, AMD, Apple, Qualcomm, MRVL custom)
- This creates geopolitical concentration risk (Taiwan) that hyperscalers are attempting to mitigate through geographic diversification of fab capacity (TSMC Arizona, Intel Foundry, Samsung Texas)

### Layer 4 — Networking evolution
The shift from InfiniBand (NVDA-owned) to Ethernet-based AI networking (Ultra Ethernet Consortium) is a major competitive shift. MRVL's Teralynx switch silicon and custom XPU designs position it well for this transition.

---

## MBA framework: Porter's Five Forces (Layer 5 — Silicon)

| Force | Assessment |
|-------|-----------|
| Supplier power | Very high — ASML monopoly on EUV, LRCX/AMAT duopoly on deposition/etch |
| Buyer power | Moderate — hyperscalers are large but dependent on NVDA roadmap |
| Competitive rivalry | Low at leading edge — NVDA vs AMD duopoly for GPUs |
| Threat of substitutes | Low near-term — custom ASICs (TPU, Trainium) serve specific workloads but can't replace general GPU compute |
| Threat of new entry | Very low — $20B+ fab capex, 5-year build timelines, deep IP moats |

---

## Investment themes (not advice)

**Picks-and-shovels logic:** MEP contractors (EME, FIX) benefit from the construction wave regardless of which AI model wins. Power infrastructure (PWR, utilities) benefits from structural electricity demand growth.

**Concentration vs diversification:** NVDA is the clearest beneficiary but carries valuation risk. TSM is a leveraged play on the entire semiconductor industry's AI transition. MRVL offers optionality through custom silicon relationships.

**Grid infrastructure:** Often overlooked — the power constraint may make electricity infrastructure (transmission, transformers, backup generation) one of the highest-returning segments of the AI CapEx build-out.

---

*For educational and analytical use. Not financial advice.*
