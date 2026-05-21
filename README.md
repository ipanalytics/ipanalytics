# ipanalytics

<p align="center">
  <img src="./assets/banner.png" alt="ipanalytics banner" width="100%">
</p>

<p align="center">
  <strong>IP intelligence, ASN analytics, GeoIP engineering, and infrastructure research</strong>
</p>

<p align="center">
  Open datasets, MMDB tooling, enrichment pipelines, and static dashboards for VPN infrastructure analysis, crawler visibility, Tor intelligence, ASN attribution, and operational network telemetry.
</p>

<p align="center">
  <a href="https://github.com/ipanalytics?tab=repositories">
    <img src="https://img.shields.io/badge/repositories-view_all-2563eb?style=for-the-badge&logo=github" alt="Repositories">
  </a>

  <a href="https://github.com/ipanalytics/IP-Knowledge-Layer">
    <img src="https://img.shields.io/badge/IP_Data-IP--Knowledge--Layer-0891b2?style=for-the-badge" alt="IP Knowledge Layer">
  </a>

  <a href="https://github.com/ipanalytics/GeoForge">
    <img src="https://img.shields.io/badge/GeoIP-GeoForge-f97316?style=for-the-badge" alt="GeoForge">
  </a>

  <a href="https://github.com/ipanalytics/CrawlerScope">
    <img src="https://img.shields.io/badge/Dashboard-CrawlerScope-16a34a?style=for-the-badge" alt="CrawlerScope">
  </a>
</p>

---

## Focus

- IP and ASN enrichment pipelines with source provenance and confidence scoring
- VPN, proxy, Tor, crawler, cloud, CDN, and hosting infrastructure analysis
- GeoIP/MMDB compilation, validation, and consensus-based enrichment
- Static dashboards and GitHub-native publishing workflows
- Operational datasets for fraud detection, SIEM enrichment, and network analytics

---

# Infrastructure Ecosystem

## Intelligence and Enrichment

| Project | Area | Description |
|---|---|---|
| [IP-Knowledge-Layer](https://github.com/ipanalytics/IP-Knowledge-Layer) | IP enrichment | Unified enrichment layer for CIDR, ASN, cloud, CDN, crawler, Tor, and VPN-adjacent infrastructure intelligence. |
| [ASN-Signal-Graph](https://github.com/ipanalytics/ASN-Signal-Graph) | ASN intelligence | Public ASN infrastructure signal aggregation for VPN overlap, Tor visibility, public feed exposure, and defensive analytics. |
| [blackroute](https://github.com/ipanalytics/blackroute) | IP reputation | Local-first pipeline for aggregating hostile IP infrastructure, abuse feeds, anonymizers, and attack telemetry into runtime lookup databases. |
| [ASN-VPN-Network-Intelligence](https://github.com/ipanalytics/ASN-VPN-Network-Intelligence) | ASN analytics | Lightweight CSV datasets for VPN infrastructure overlap and ASN/provider enrichment workflows. |

---

## GeoIP and MMDB Tooling

| Project | Area | Description |
|---|---|---|
| [GeoForge](https://github.com/ipanalytics/GeoForge) | GeoIP / MMDB | Consensus-based GeoIP compiler combining GeoLite2, DB-IP, IP2Location, Sypex Geo, GeoNames, geofeeds, and RIR metadata into reproducible MMDB outputs. |
| [MMDBForge](https://github.com/ipanalytics/MMDBForge) | MMDB tooling | Toolkit for inspecting, validating, diffing, and analyzing MaxMind DB files and custom MMDB datasets. |
| [MMDB-WatchTower](https://github.com/ipanalytics/MMDB-WatchTower) | MMDB operations | Production-safe MMDB updater with validation, atomic swaps, rollback support, smoke tests, and Prometheus metrics. |

---

## Dashboards and Visibility

| Project | Area | Description |
|---|---|---|
| [CrawlerScope](https://github.com/ipanalytics/CrawlerScope) | Crawler intelligence | Static dashboard and dataset for crawler, AI bot, monitoring probe, and scanner infrastructure visibility. |
| [Tor-Radar](https://github.com/ipanalytics/Tor-Radar) | Tor intelligence | GitHub-native Tor relay analytics dashboard with historical network snapshots and relay metadata. |
| [VPN-Infrastructure-Atlas](https://github.com/ipanalytics/VPN-Infrastructure-Atlas) | VPN atlas | Interactive VPN infrastructure atlas showing aggregate provider footprint by country, ASN, and hosting network. |

---

## VPN Infrastructure Research

| Project | Area | Description |
|---|---|---|
| [vpn-provider-overlap-intelligence](https://github.com/ipanalytics/vpn-provider-overlap-intelligence) | VPN analytics | Aggregate analysis of VPN provider overlap, hosting concentration, provider clustering, and shared infrastructure signals. |

---

## Infrastructure Themes

```text
IP ranges
    -> ASN attribution
    -> infrastructure classification
    -> VPN overlap analysis
    -> crawler visibility
    -> Tor intelligence
    -> GeoIP enrichment
    -> reputation signals
    -> operational datasets
````

Research areas include:

* VPN infrastructure overlap
* ASN concentration and hosting dependency
* crawler and AI fetcher identification
* GeoIP/MMDB quality engineering
* CIDR normalization and enrichment
* infrastructure provenance and confidence scoring
* public signal aggregation and enrichment

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,linux,docker,git,githubactions&perline=10" alt="Stack">
</p>

### Formats

`CSV` `JSON` `JSONL` `Parquet` `MMDB` `CIDR`

### Network Metadata

`ASN` `BGP` `RIR` `WHOIS` `GeoIP` `GeoFeed`

### Infrastructure Signals

`VPN` `Proxy` `Tor` `Crawler` `Cloud` `CDN` `Hosting` `Reputation`

---

## Current Work

* Building reproducible enrichment pipelines with auditable source attribution
* Expanding ASN-level infrastructure signal aggregation
* Improving VPN overlap analysis without publishing raw VPN inventories
* Building local-first GeoIP, reputation, and MMDB operations tooling
* Publishing compact operational datasets optimized for SIEM, fraud, and analytics workflows

---

## Design Principles

| Principle           | Description                                                          |
| ------------------- | -------------------------------------------------------------------- |
| Reproducibility     | Deterministic dataset generation and traceable inputs                |
| Operational Utility | Lightweight exports for pipelines and local lookups                  |
| Source Transparency | Preserve provenance and confidence metadata                          |
| Static Deployment   | Prefer GitHub-native publishing and browser-only dashboards          |
| Defensive Focus     | Infrastructure intelligence for analytical and operational workflows |

---

## GitHub Analytics

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ipanalytics&theme=github_dark" alt="GitHub profile summary">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ipanalytics&theme=dark&hide_border=true" height="160" alt="GitHub streak">
</p>

---

## Collaboration

Open to:

* dataset feedback
* enrichment methodology discussion
* GeoIP/MMDB quality analysis
* ASN and VPN infrastructure research
* crawler and bot intelligence collaboration
* SIEM and fraud enrichment integrations

If you work with IP telemetry, routing metadata, fraud systems, abuse detection, or operational network analytics, feel free to open an issue or discussion in the relevant repository.

---

## Licensing

Licensing varies by repository depending on source constraints and redistribution requirements.

Most repositories use:

* Apache-2.0 for code
* CC0-1.0 for generated datasets

See the license files in each repository for details.


