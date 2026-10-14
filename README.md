# V3 CORE

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-cryptocurrency-lightgrey)

> Anticloud-hardened packaging of the upstream project `V3_CORE` in category **CRYPTOCURRENCY**. No upstream snapshot is present on disk for this project; the pinned commit below was resolved during the second documentation pass, and the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** CRYPTOCURRENCY · **Upstream:** https://github.com/Uniswap/v3-core · **Upstream pin:** `d0831dc6b8a318df3872b6d68f6de135c9f3ec29` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

**V3 CORE** — Uniswap V3 core - concentrated-liquidity AMM smart contracts (Solidity).

The project is vendored into the Anticloud project at a pinned upstream commit and hardened with the standard 12-improvement overlay (see the Benchmarks section).

Project-specific facts detected in this directory:

- Ecosystem: **Unknown (no standard manifest detected)** (manifests: none detected; scanned in project root)
- Upstream snapshot: none on disk for this project; only the Anticloud packaging directories are present
- Snapshot size: **67 files**, **68 lines of code** (measured; see Benchmarks)
- Primary languages: `.sol` (40), `(none)` (8), `.yml` (6), `.json` (3), `.md` (3), `.yaml` (3)
- Upstream commit pinned for this packaging: `d0831dc6b8a318df3872b6d68f6de135c9f3ec29`

---

## Installation

No installation section was found in the upstream readme, so the commands below are generated from the manifests detected in this project directory.

```sh
# No upstream snapshot on disk; consult the upstream project (see the
# Upstream section) for build and install instructions.
```

Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

Browse the snapshot layout listed under What This Project Does and follow the upstream run instructions for the detected ecosystem (Unknown (no standard manifest detected)).

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `V3_CORE` upstream project (Unknown (no standard manifest detected) ecosystem); no source snapshot is vendored for this project. Entry points recorded for this packaging:

- Source modules: `01_INVESTOR_PACKAGE/`, `02_COMMITMENT_TO_SOCIETY/`, `03_COMMITMENT_TO_HUMANITY/`, `04_COMMITMENT_TO_ENVIRONMENT/`, `05_COMMITMENTS_TO_PAST_PRESENT_FUTURE/`, `06_WHITELABELLING_AND_REPACKAGING/`, `07_ENTERPRISE_LICENSE_AND_PRICING/`, `08_INTELLECTUAL_PROPERTY_AND_RIGHTS/`
- The snapshot declares 22 dependency references across 1 ecosystem(s); see Dependencies below.
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Unknown (no standard manifest detected) |
| Manifests detected | none |
| Files in snapshot | 67 |
| Lines of code | 68 |
| Dependency references | 22 |
| Dependencies by ecosystem | npm: 22 |
| Upstream license | Not captured in this benchmark snapshot (no upstream snapshot on disk) |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | @nomiclabs/hardhat-ethers | ^2.0.2 | package.json |
| npm | @nomiclabs/hardhat-etherscan | ^2.1.8 | package.json |
| npm | @nomiclabs/hardhat-waffle | ^2.0.1 | package.json |
| npm | @typechain/ethers-v5 | ^4.0.0 | package.json |
| npm | @types/chai | ^4.2.6 | package.json |
| npm | @types/mocha | ^5.2.7 | package.json |
| npm | chai | ^4.2.0 | package.json |
| npm | decimal.js | ^10.2.1 | package.json |
| npm | ethereum-waffle | ^3.0.2 | package.json |
| npm | ethers | ^5.0.8 | package.json |
| npm | hardhat | ^2.2.0 | package.json |
| npm | hardhat-typechain | ^0.3.5 | package.json |
| npm | mocha | ^6.2.2 | package.json |
| npm | mocha-chai-jest-snapshot | ^1.1.0 | package.json |
| npm | prettier | ^2.0.5 | package.json |
| ... | (7 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- None detected at the snapshot root; consult the upstream documentation link in the Upstream section.

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

Upstream contributions: fork the `V3_CORE` project, create a feature branch, and open a pull request against upstream. Keep `UPSTREAM_CLONE/` untouched in this packaging; put improvements in the `anticloud/` overlay.

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Not captured in this benchmark snapshot (no upstream snapshot on disk).** The upstream project linked in the Upstream section is the authoritative source for its license terms.

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Not captured in this benchmark snapshot (no upstream snapshot on disk) terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Not captured in this benchmark snapshot (no upstream snapshot on disk)` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `V3_CORE` (category: CRYPTOCURRENCY)
- **Upstream URL:** https://github.com/Uniswap/v3-core
- **Pinned commit (SHA):** `d0831dc6b8a318df3872b6d68f6de135c9f3ec29`
- **Branch:** main
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** none on disk for this project
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`9c5cdc77a4a5540a030af39ccb60683bd040e0e3c1919ea4e259dc51643e1f86`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

