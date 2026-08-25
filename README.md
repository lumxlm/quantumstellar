
# ⚛️ Quantum Computing Landscape — Reference Guide

A curated, comparative overview of key companies shaping the quantum computing and quantum-safe security industry, built for developers and researchers who want a quick map of who does what.

> 📌 **Purpose:** This is an educational/reference document — a "who's who" of the quantum industry. It does not represent any partnership, endorsement, or affiliation with the companies listed. All information is sourced from public company materials and industry coverage as of mid-2026 and may change; always verify against the company's own site before citing elsewhere.

---

## 📑 Table of Contents

- [Hardware Manufacturers](#-hardware-manufacturers)
- [Cloud & Platform Access](#-cloud--platform-access)
- [Software, Error Correction & Control](#-software-error-correction--control)
- [Quantum-Safe Security](#-quantum-safe-security)
- [A Note on Ambiguous / Unrelated Names](#-a-note-on-ambiguous--unrelated-names)
- [Comparison Table](#-comparison-table)
- [Further Reading](#-further-reading)

---

## 🖥️ Hardware Manufacturers

### IonQ
Builds gate-based quantum computers using **trapped-ion** technology, marketed for high gate fidelity relative to some competing approaches. IonQ is publicly traded (NYSE: IONQ) and offers cloud access to its systems through major cloud marketplaces. It has also expanded into quantum networking and, more recently, quantum-safe security through acquisitions in that space.

### D-Wave
Focuses on **quantum annealing** hardware, a specialized approach aimed primarily at optimization problems rather than general-purpose gate-based computing. D-Wave is publicly traded (NYSE: DWAV) and has one of the longest commercial track records in the industry, with systems used for logistics, scheduling, and materials research.

### Atom Computing
Develops gate-based quantum computers using **neutral-atom arrays**, an architecture that allows for large numbers of qubits arranged in optical tweezers. The approach is notable for scaling qubit counts relatively quickly compared to some other hardware modalities.

### Infleqtion (formerly ColdQuanta)
Originally founded in 2007 in Boulder, Colorado as ColdQuanta, the company rebranded to **Infleqtion** in 2022 to reflect its shift from research into commercial products. It builds neutral-atom quantum computers, quantum sensors (including optical clocks and RF sensors), and quantum networking hardware. In February 2026, Infleqtion completed a SPAC merger and began trading on the NYSE under the ticker **INFQ**, becoming the first neutral-atom quantum company to go public. Its customers and partners include NASA and the U.S. Department of Defense.

### PsiQuantum
Pursuing a **photonic** approach to fault-tolerant quantum computing, PsiQuantum is a private company known for pairing its hardware roadmap with large-scale semiconductor manufacturing partnerships, aiming to skip smaller intermediate systems in favor of building toward a large, error-corrected machine.

### IBM Quantum
IBM's quantum division builds **superconducting-qubit** hardware and has one of the longest-running cloud-accessible quantum programs in the industry, dating back to 2016. IBM publishes a public hardware roadmap targeting increasing qubit counts and error-correction milestones through the rest of the decade.

### Quantum Computing Inc. (QCI)
A publicly traded company (NASDAQ: QUBT) pursuing photonic and reservoir-computing approaches to quantum and quantum-inspired computing, with a focus on niche applications like remote sensing (LiDAR) alongside its computing hardware line.

---

## ☁️ Cloud & Platform Access

### IBM Quantum Network
IBM's partner program that gives select organizations — enterprises, universities, and national labs — extended access to IBM's quantum hardware and research collaboration beyond the standard public cloud tier.

### Microsoft Azure Quantum
Microsoft's cloud platform for quantum computing, offering access to third-party hardware (rather than a single in-house device) alongside Microsoft's own quantum software stack (Q#, the Azure Quantum SDK) and, more recently, its own topological-qubit research efforts.

### Amazon Braket
AWS's quantum computing service, providing a single API and console to access multiple third-party quantum hardware providers alongside simulators, aimed at letting developers prototype quantum algorithms without managing hardware relationships individually.

---

## 🛠️ Software, Error Correction & Control

### Riverlane
A UK (Cambridge) company building **Deltaflow**, a real-time quantum error correction stack designed to work across different hardware types ("hardware-agnostic"). Riverlane has raised more than $120M and reports partnerships with a large share of quantum hardware companies, since QEC is a shared bottleneck across the whole industry rather than something any single hardware vendor can solve alone.

### Q-CTRL
An Australia-based company (Sydney/Chippendale) building infrastructure software that improves the performance of quantum hardware — reducing error rates in existing machines — as well as quantum-sensing applications like GPS-independent navigation.

### Entropica Labs
A Singapore-based software company focused specifically on the **compiler and tooling layer** for quantum error correction — translating logical-qubit circuits into something real hardware can execute, aimed at closing the gap between QEC theory and usable fault-tolerant systems.

### 1QBit
Founded in 2012 in Vancouver, 1QBit is one of the earliest dedicated quantum software companies, building hardware-agnostic optimization and machine-learning algorithms that run across different quantum and quantum-inspired backends (including D-Wave and IBM systems). Its clients span finance, chemicals, and life sciences.

---

## 🔐 Quantum-Safe Security

### Quantropi
An Ottawa, Canada-based company founded in 2018, Quantropi builds quantum-safe cryptography aimed at protecting data against both classical attacks today and future quantum-computer attacks — including the "harvest now, decrypt later" threat model, where encrypted data is collected today with the intent of decrypting it once quantum computers are powerful enough. Its **QiSpace** platform combines post-quantum cryptography, quantum-secure symmetric encryption, and quantum random number generation, and it has public integration partnerships with companies like Nokia.

---

## ❓ A Note on Ambiguous / Unrelated Names

A few names from the original request don't map cleanly onto a specific company in this space, so they're flagged rather than guessed at:

- **Starlink** — this is SpaceX's satellite internet constellation, not a quantum computing company. It isn't included above since it's unrelated to this list's subject matter.
- **"Qubit"** — this is the generic term for a quantum bit (the basic unit of quantum information), not a company name.
- **"QuantumComp"** — too generic to map to one specific company; if you meant a particular one (e.g. Quantum Computing Inc.), let me know and I'll expand that section.

---

## 📊 Comparison Table

| Company | Category | Core Technology | Public/Private |
|---|---|---|---|
| IonQ | Hardware | Trapped-ion | Public (IONQ) |
| D-Wave | Hardware | Quantum annealing | Public (DWAV) |
| Atom Computing | Hardware | Neutral atoms | Private |
| Infleqtion (ex-ColdQuanta) | Hardware | Neutral atoms | Public (INFQ) |
| PsiQuantum | Hardware | Photonics | Private |
| IBM Quantum | Hardware / Cloud | Superconducting | Public (IBM) |
| Quantum Computing Inc. | Hardware | Photonic / reservoir | Public (QUBT) |
| Microsoft Azure Quantum | Cloud platform | Multi-vendor access | Public (MSFT) |
| Amazon Braket | Cloud platform | Multi-vendor access | Public (AMZN) |
| Riverlane | Software | Error correction | Private |
| Q-CTRL | Software | Error suppression / sensing | Private |
| Entropica Labs | Software | QEC compilers | Private |
| 1QBit | Software | Optimization / ML | Private |
| Quantropi | Security | Quantum-safe cryptography | Private |

---

## 📚 Further Reading

- Each company's own investor-relations or newsroom page (linked from their official site) is the most reliable source for current funding, roadmap, and hardware specs — those numbers move quickly in this industry.
- If this reference guide is meant to accompany a separate token or blockchain project, keep that content in its own README rather than mixing it with this industry overview; conflating an unrelated token pitch with a factual industry reference tends to undermine the credibility of both.

---

## ⚖️ Disclaimer

This document is for informational purposes only. It is not affiliated with, endorsed by, or sponsored by any of the companies named above. Company names and trademarks belong to their respective owners. Details (funding, tickers, roadmaps) are current as of mid-2026 and should be independently verified before being relied upon.
