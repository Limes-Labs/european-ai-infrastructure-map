# European AI Infrastructure Map

> Living public map maintained by [Limes Labs](https://limeslabs.eu). Last updated: June 2026.

We are not claiming compute access. We are documenting what exists and what paths are worth pursuing.

## Quick links

| Resource | URL |
| --- | --- |
| EuroHPC access portal | https://access.eurohpc-ju.europa.eu/ |
| EuroHPC systems factsheets | https://eurohpcsupport.eu/eurohpc/eurohpc-systems/ |
| AI Factories overview | https://www.eurohpc-ju.europa.eu/ai-factories_en |
| AI Factories systems | https://www.eurohpc-ju.europa.eu/ai-factories/ai-factories-systems_en |
| AI Factories access modes | https://www.eurohpc-ju.europa.eu/ai-factories/ai-factories-access-modes_en |
| Large Scale Access (industrial) | https://www.eurohpc-ju.europa.eu/large-scale-access-ai-factories_en |
| IT4LIA (Italy) | https://it4lia-aifactory.eu/ |
| LUMI docs | https://www.lumi-supercomputer.eu/ |
| Leonardo docs | https://leonardo-supercomputer.cineca.eu/ |
| JUPITER docs | https://www.fz-juelich.de/en/ias/jsc/jupiter |
| EU Open Source Strategy | https://digital-strategy.ec.europa.eu/en/policies/open-source-strategy |
| Limes Labs open questions | https://limeslabs.eu/open-questions |

---

## 1. EuroHPC supercomputers (operational & incoming)

Source: [EuroHPC JU — Our Supercomputers](https://www.eurohpc-ju.europa.eu/supercomputers/our-supercomputers_en), TOP500 / EuroHPC press (June 2026).

| System | Country | Host | Class | Notes |
| --- | --- | --- | --- | --- |
| **JUPITER** | Germany | JSC / Forschungszentrum Jülich | Exascale (~1 EF) | Europe's fastest (TOP500 #4, 2025); **JAIF** AI Factory; BullSequana XH3000 |
| **LUMI** | Finland | CSC, Kajaani | Pre-exascale (~380 PF) | TOP500 top 10; **LUMI AI Factory**; HPE Cray EX |
| **Leonardo** | Italy | CINECA, Bologna Tecnopolo | Pre-exascale (~241 PF) | TOP500 top 10; **IT4LIA**; **LISA** AI partition deploying |
| **MareNostrum 5** | Spain | BSC, Barcelona | Pre-exascale | AI Factory via upgrade; ACC GPU partition for large models |
| **MeluXina** | Luxembourg | LuxProvide, Bissen | Petascale | **MeluXina-AI** factory |
| **Karolina** | Czechia | IT4Innovations, Ostrava | Petascale | HPE Apollo; EuroHPC access |
| **Discoverer** | Bulgaria | Sofia Tech Park | Petascale | BullSequana XH2000 |
| **Deucalion** | Portugal | FCT / MACC | Petascale | AI & climate workloads |
| **Vega** | Slovenia | IZUM, Maribor | Petascale | BullSequana XH2000 |
| **Alice Recoque** | France | CEA TGCC (GENCI consortium) | Exascale (incoming) | Deploy from 2026; **AI2F** France; Eviden Sequana XH3500 |
| **Arrhenius** | Sweden | NAIS Sweden | Mid-range (incoming) | Ops early 2026; paired with **MIMER** AI Factory |
| **Daedalus** | Greece | GRNET | Incoming | Associated with Greek AI Factory / **Pharos** |

**Access:** European users in Member States or countries associated to DEP/Horizon Europe may apply via https://access.eurohpc-ju.europa.eu/

**Policy reference:** [EuroHPC Access Policy (April 2025 PDF)](https://www.eurohpc-ju.europa.eu/document/download/a473e939-1131-4a75-bf0b-4d8659d6bce0_en)

---

## 2. EuroHPC AI Factories network

The EU is building **AI Factories** — open ecosystems around AI-optimised supercomputers with **free customised support for SMEs and startups** (EuroHPC JU, 2026). **13 sites** were selected in 2024–2025; additional factories in Austria, Bulgaria, France, Germany, Poland, Slovenia (March 2025 cut-off). **19 AI Factories** and **13 Antennas** referenced in 2026 communications.

AI Factories provide: GPU compute, expert support, training, data/compliance tooling, and industry/science networking.

### First-wave national AI Factories (Dec 2024 selection)

| Factory | Country | Lead / host | Base system | Status (2026) |
| --- | --- | --- | --- | --- |
| **LUMI AI Factory** | Finland | CSC | New AI system + LUMI | Operational; experimental platform |
| **JAIF** | Germany | JSC | JUPITER + new AI partition | Selected Mar 2025 |
| **IT4LIA** | Italy | CINECA | Leonardo, LISA, new Dell/E4 system | Services since Apr 2025; €290M new AI system contract Apr 2026 |
| **MeluXina-AI** | Luxembourg | LuxProvide | MeluXina + new AI system | Deploying |
| **MIMER** | Sweden | Linköping / NAIS | New AI-dedicated system + Arrhenius | Life sciences, healthcare, materials focus |
| **BSC AI Factory** | Spain | BSC | MareNostrum 5 upgrade | GPU ACC partition |
| **Pharos / DAEDALUS** | Greece | GRNET | Daedalus supercomputer | AI-ready national stack |

### Additional AI Factories (2025 selections)

| Factory | Country | Notes |
| --- | --- | --- |
| **AI2F** | France | Alice Recoque; interim access via Jean Zay, Adastra, Joliot-Curie |
| **HammerHAI** | Germany | Complements JAIF |
| **PIAST** | Poland | National sovereign AI |
| **Gaia AI Factory** | Poland | Additional factory |
| **CZAI** | Czechia | New |
| **LitAI** | Lithuania | New |
| **NLAIF** | Netherlands | New |
| **1Health AI** | Spain | Health vertical |
| **RO AI Factory** | Romania | New |
| Austria, Bulgaria, Slovenia | — | New AI-optimised systems per Mar 2025 announcement |

**Antennas** extend factories transnationally (e.g. IT4LIA antennas: Switzerland, Serbia). Full list: https://www.eurohpc-ju.europa.eu/ai-factory-antennas_en

---

## 3. AI Factories access modes

Source: [EuroHPC AI Factories Access Modes](https://www.eurohpc-ju.europa.eu/ai-factories/ai-factories-access-modes_en)

### A. Industrial Innovation (startups / SMEs)

**Free** for eligible AI SMEs and startups pursuing innovation:

| Tier | GPU hours | Audience |
| --- | --- | --- |
| **Playground** | Entry-level | First experiments |
| **Fast Lane** | Up to **50,000** GPU hours | HPC-familiar teams |
| **Large Scale** | **> 50,000** GPU hours | Foundation-model-scale work; 3–12 month allocations |

- **Apply:** https://access.eurohpc-ju.europa.eu/
- **Large Scale call** (2025–2027 rolling cut-offs): industrial innovation track; resources quoted in GPU-hours per system partition.
- **Availability note (2026):** Leonardo and MareNostrum 5 partitions may be constrained under high demand — check current partition availability at application time.

Other industrial use → commercial pay-per-use via hosting sites.

### B. AI for Science & Collaborative EU Projects

Free for eligible users in publicly funded research / DEP / Horizon Europe collaborative projects.

### C. Strategic / urgent / federation

Additional EuroHPC access tracks exist for strategic initiatives and federation platform users — see access portal and [Federation Platform release (Apr 2026)](https://www.eurohpc-ju.europa.eu/first-release-eurohpc-federation-platform-streamline-access-europes-supercomputing-resources-2026-04-15_en).

### Eligibility snapshot

- Users must be in **EU Member States** or countries **associated to DEP or Horizon Europe**
- Industrial innovation large-scale: applicants should be **industry** (incl. startups/SMEs) resident/located in eligible countries
- Open-source projects without legal entity may need a **partner university, research org, or company** — *Limes Labs is documenting paths; not yet claiming eligibility*

---

## 4. IT4LIA (Italy) — detailed

Sources: [it4lia-aifactory.eu](https://it4lia-aifactory.eu/), [EuroHPC IT4LIA contract (Apr 2026)](https://www.eurohpc-ju.europa.eu/eurohpc-ju-signs-contract-boost-ai-capabilities-it4lia-ai-factory-2026-04-22_en), [LISA upgrade](https://www.eurohpc-ju.europa.eu/eurohpc-joint-undertaking-awards-contract-lisa-upgrade-leonardo-supercomputer-2025-05-13_en)

**Consortium:** CINECA (lead), ARNES (Slovenia), ACA (Austria), AIT (Austria). **Location:** DAMA Tecnopolo, Bologna (+ MEGARIDE node in Naples).

### Infrastructure continuum

| System | Role |
| --- | --- |
| **Leonardo** | EuroHPC pre-exascale; ~250 PF peak; Booster + data-centric modules |
| **LISA** | First EuroHPC partition designed for AI; ~650 PF mixed-precision; 8-GPU nodes, 640GB+ HBM; deployed 2025 |
| **GAIA** | Cloud / hybrid layer |
| **MEGARIDE** | University campus GPU capacity (Naples) |
| **New AI system (2026)** | Dell/E4 contract; >160 EF inference peak cited; integrated with EuroHPC |

### Services (horizontal + vertical)

Verticals: agritech, cybersecurity, meteorology/climate, manufacturing. Horizontal: secure data management, metadata, **EU/IT regulatory compliance** checks, training, agentic AI support.

### Packages

| Package | Use case |
| --- | --- |
| **TRY** | Experimentation, scalability trials |
| **Medium** | Fine-tuning, datasets, agentic prototypes |
| **Large** | Pre-training, foundation-model adaptation |

**No fixed usage cap** for eligible users through **31 March 2028** (per IT4LIA FAQ).

### Contacts

| Purpose | Contact |
| --- | --- |
| General | info-it4lia@cineca.it |
| Technical support | support-it4lia@cineca.it |
| Training | training-it4lia@cineca.it |
| Consultation form | https://forms.office.com/e/swchU8P4C5 |
| Address | Via Stalingrado 84/3, 40128 Bologna |

---

## 5. Other notable national / regional stacks

| Initiative | Country | Notes |
| --- | --- | --- |
| **GenAI4EU** | EU-wide | Uptake of generative AI across industrial ecosystems |
| **OpenEuroLLM** | EU consortium | 20+ orgs; multilingual open LLMs; first models mid-2026 |
| **Mistral Compute** | France | EU cloud / API infrastructure |
| **Scaleway / OVHcloud** | France | Sovereign EU GPU hosting for open-weight inference |
| **Nebius** | EU operations | GPU cloud (NL/Finland presence) |
| **Tilde on LUMI** | Latvia/EU | TildeOpen 30B trained on LUMI (2M GPU hours, Sep 2025) — example of factory outcomes |

---

## 6. EU policy context (why this map matters)

- **AI Act** (Reg. 2024/1689): risk-based rules; GPAI obligations from Aug 2025; full applicability Aug 2026
- **EU Open Source Strategy** (2026): open source as lever for **technological sovereignty**
- **Cloud and AI Development Act (CADA)**: sovereign cloud/AI stack proposal
- **European Technological Sovereignty Package** (2026): semiconductors, AI, cloud, open source

Limes Labs hypothesis: **open weights + EuroHPC access + public eval (eurobench)** is a viable European path that does not require pretending frontier labs already exist everywhere.

---

## 7. Open gaps (where Limes Labs needs help)

- [ ] Confirm legal-entity requirements for unaffiliated open-source collectives (Fast Lane vs Large Scale)
- [ ] Document per-factory single points of contact for open-model pretraining proposals
- [ ] GPU-hour budgeting template for 7B / 30B / 70B European language runs
- [ ] Map national funding (PNRR Italy, France 2030, etc.) that stacks with EuroHPC allocations
- [ ] Track **Federation Platform** onboarding for non-traditional applicants
- [ ] Public contact log (what we asked, what we learned) → see [compute-access-notes](https://github.com/Limes-Labs/compute-access-notes)

## Contribute

- Open an issue with a program, lab, or access path to document
- Submit a PR with **sourced** notes (link + date)
- Join: https://limeslabs.eu/join