<h1 align="center">Aibek Shokanuly</h1>

<p align="center">
  <strong>I build systems that have to prove their own claims.</strong><br />
  Student engineer in Temirtau, Kazakhstan: software for payments, construction and industry,<br />
  tested until it breaks, then put on hardware.
</p>

<p align="center">
  <a href="https://chainstory-iota.vercel.app/tripwire?incident=kelp"><strong>▶ Tripwire replay</strong></a> ·
  <a href="https://horkos-murex.vercel.app"><strong>▶ Horkos live demo</strong></a> ·
  <a href="#what-im-building">Projects</a> ·
  <a href="#selected-results">Results</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-strict-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Solidity-363636?logo=solidity&logoColor=white" alt="Solidity" />
  <img src="https://img.shields.io/badge/C%2B%2B-ESP32%20%C2%B7%20Arduino-00599C?logo=cplusplus&logoColor=white" alt="C++ on ESP32 and Arduino" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React%20%C2%B7%20Next.js-20232A?logo=react&logoColor=61DAFB" alt="React and Next.js" />
</p>

---

> [!NOTE]
> Representing Kazakhstan at the **Fibonacci International Robot Olympiad World Final**, Rome, November 2026.

## At a glance

| | |
| :--- | :--- |
| **$313.6M → $0** | Three real 2026 bridge exploits replayed through [Tripwire](https://github.com/shokkanuly/Chainstory): each drain is stopped before execution |
| **1,787 tests · 111 / 111 mutants caught** | Tripwire's safety rules are broken on purpose by a script, and a test catches every break |
| **Live on two testnets** | Tripwire on Sepolia (owned by a Safe multisig), [Horkos](https://github.com/shokkanuly/verimesh) on Monad, with every contract source-verified |
| **3× more late deliveries flagged** | [SitePulse](https://github.com/shokkanuly/delivery-delay) "red" deliveries ran late 74.5% of the time vs 24.4% for "green", on a synthetic benchmark |
| **87.9% on 24 ASL letters** | [Collector](https://github.com/shokkanuly/Collector), scored on recording sessions the model never saw, so the number isn't inflated by leakage |

Every number links to a repository where you can reproduce it. Where the data is synthetic or the hardware isn't built yet, the README says so.

## What I'm building

| Project | What it does | Status | Stack |
| :--- | :--- | :--- | :--- |
| **[Tripwire](https://github.com/shokkanuly/Chainstory)** | Checks every cross-chain USDC payout before it executes: source backing, independent screening, customer policy | Live on Sepolia · CI green | Solidity · TypeScript |
| **[Horkos](https://github.com/shokkanuly/verimesh)** | Binds signed machine verdicts to an on-chain agent identity, so applications can enforce their own trust rules | Live on Monad testnet · synthetic inputs | Solidity · TypeScript |
| **[SitePulse](https://github.com/shokkanuly/delivery-delay)** | Tells a construction site which deliveries will slip and assigns cranes without clashes | Working software · synthetic data · no pilot signed yet | Python · FastAPI · OR-Tools |
| **[Collector](https://github.com/shokkanuly/Collector)** | Reads ASL fingerspelling from a webcam; a servo hand that signs it back is in progress | Recognizer done · hand firmware next | Python · PyTorch · Arduino |
| **[Smart Agri Monitor](https://github.com/shokkanuly/Smart-Agri-Monitor-Optimization-System)** | Soil telemetry and irrigation advice for water-scarce farms | Runs on a simulator · hardware next | C++ · ESP32 · FastAPI |
| **[Astana Twin](https://github.com/shokkanuly/KHA-DIVERGENT-AI-electric-traffic-monitoring-system)** | A city twin for traffic, fleet and structural monitoring | Research prototype | Python · FastAPI · ESP32 |

**In private development:** an industrial digital twin for mining and metallurgy (15 engineering cases, each with hand-derived known-answer tests), and **Nakty**, labor-law checks for Kazakh businesses.

## How I work

- **Tests that can fail.** A rule isn't done until a test with a known answer pins it. One such test caught a parser that read "the 15th" as "the 5th" and called a late salary legal.
- **Attack my own code.** Tripwire's contracts were audited, broken with mutation scripts, and killed mid-write to see what survives.
- **Say what is simulated.** Synthetic data and unbuilt hardware are labelled in every README, next to the number they affect.

## Selected results

- 🥇 1st place, national stage: Fibonacci International Congress (ITECX)
- 🥇 1st place: Republican Informatics Olympiad
- 🥈 2nd place: Republican Physics Olympiad
- 🥇 1st place: Regional Research Defense in Mathematics, Buketov Karaganda University
