
<div align="center">

# IP Analytics

<p>
  <img src="./assets/banner.png" alt="IP Analytics banner" width="100%">
</p>

**IP intelligence, ASN analytics, routing security, GeoIP/MMDB engineering, and infrastructure research**

Open datasets, static dashboards, routing-security tooling, enrichment pipelines, GeoIP/MMDB workflows, and operational network intelligence systems.



</div>

---

# Focus Areas

- IP and ASN enrichment with provenance and confidence scoring
- VPN, proxy, Tor, crawler, cloud, CDN, and hosting infrastructure analysis
- BGP, RPKI, ROA, and routing-security visibility
- GeoIP/MMDB compilation, validation, diffing, and operational tooling
- Geofeed discovery and routing-aware geolocation enrichment
- Static dashboards, APIs, and GitHub-native publishing workflows
- Operational datasets for SIEM, fraud detection, OSINT, and network analytics

---

# Infrastructure Ecosystem

## Infrastructure Intelligence

| Project | Description |
|---|---|
| [IP-Knowledge-Layer](https://github.com/ipanalytics/IP-Knowledge-Layer) | Open enrichment layer for CIDR, ASN, cloud, CDN, crawler, Tor, VPN, and infrastructure intelligence with provenance and confidence scoring. |
| [ASN-Signal-Graph](https://github.com/ipanalytics/ASN-Signal-Graph) | ASN-level infrastructure signal aggregation for VPN overlap, Tor visibility, public-feed exposure, and defensive analytics. |
| [blackroute](https://github.com/ipanalytics/blackroute) | Local-first hostile infrastructure and reputation intelligence pipeline with MMDB and CSV outputs. |
| [ASN-VPN-Network-Intelligence](https://github.com/ipanalytics/ASN-VPN-Network-Intelligence) | VPN infrastructure overlap and ASN/provider enrichment datasets. |

---

## VPN Infrastructure Research

| Project | Description |
|---|---|
| [VPN-Infrastructure-Intelligence-Lab](https://github.com/ipanalytics/VPN-Infrastructure-Intelligence-Lab) | Aggregate VPN infrastructure intelligence dashboard for provider, ASN, country, and hosting dependency analysis. |
| [vpn-provider-overlap-intelligence](https://github.com/ipanalytics/vpn-provider-overlap-intelligence) | Shared infrastructure and provider overlap analysis across ASNs, prefixes, and hosting networks. |

---

## Routing Security and Internet Measurements

| Project | Description |
|---|---|
| [RouteSentinel](https://github.com/ipanalytics/RouteSentinel) | Daily route-security snapshot analyzer for BGP RIB dumps and RPKI VRP datasets. |
| [GeoFeed-Harvester](https://github.com/ipanalytics/GeoFeed-Harvester) | RFC 8805 geofeed discovery, validation, provenance tracking, and routing-aware geolocation analysis from public RIR data. |

---

## Dashboards and Visibility

| Project | Description |
|---|---|
| [CrawlerScope](https://github.com/ipanalytics/CrawlerScope) | Interactive crawler intelligence dashboard for AI crawlers, search bots, scanners, and monitoring probes. |
| [Tor-Radar](https://github.com/ipanalytics/Tor-Radar) | Browser-only Tor relay intelligence dashboard with compact snapshots and relay metadata. |

---

## GeoIP and MMDB Tooling

| Project | Description |
|---|---|
| [GeoForge](https://github.com/ipanalytics/GeoForge) | Consensus-based GeoIP compiler combining GeoLite2, DB-IP, IP2Location, geofeeds, RIR, and WHOIS signals. |
| [MMDBForge](https://github.com/ipanalytics/MMDBForge) | Toolkit for inspecting, validating, diffing, and analyzing MaxMind DB and custom MMDB datasets. |
| [MMDB-WatchTower](https://github.com/ipanalytics/MMDB-WatchTower) | Production-safe MMDB updater with validation, rollback, atomic swaps, smoke tests, and Prometheus metrics. |

---

## Privacy and Security Tooling

| Project | Description |
|---|---|
| [PrefixCloak](https://github.com/ipanalytics/PrefixCloak) | Prefix-preserving IPv4/IPv6 sanitizer for logs, telemetry, SIEM exports, and subnet-safe anonymization workflows. |

---

# Infrastructure Model

```text
IP ranges
  -> CIDR normalization
  -> ASN attribution
  -> BGP and RPKI validation
  -> geofeed discovery
  -> hosting and cloud classification
  -> VPN / proxy / Tor / crawler signals
  -> GeoIP and MMDB enrichment
  -> reputation and abuse context
  -> dashboards, CSV exports, static APIs, and lookup databases
````

---

# Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,js,html,linux,docker,git,githubactions&perline=10" alt="Stack">
</p>

### Formats

`CSV` `JSON` `JSONL` `Parquet` `MMDB` `CIDR`

### Network Metadata

`ASN` `BGP` `RPKI` `ROA` `RIR` `WHOIS` `GeoIP` `GeoFeed`

### Infrastructure Signals

`VPN` `Proxy` `Tor` `Crawler` `Cloud` `CDN` `Hosting` `Scanner` `Reputation`

---

# Current Work

* Expanding ASN-level infrastructure signal aggregation
* Building routing-security visibility around BGP and RPKI validation
* Developing geofeed discovery and provenance pipelines
* Improving VPN overlap analysis without publishing raw endpoint inventories
* Building local-first GeoIP, MMDB, and reputation tooling
* Publishing compact operational datasets for SIEM and analytics workflows

---

# Design Principles

| Principle           | Description                                            |
| ------------------- | ------------------------------------------------------ |
| Reproducibility     | Deterministic dataset generation with auditable inputs |
| Source Transparency | Preserve provenance and confidence metadata            |
| Operational Utility | Lightweight exports for pipelines and local lookups    |
| Static Deployment   | Prefer GitHub-native dashboards and APIs               |
| Defensive Focus     | Infrastructure intelligence for analytical workflows   |

---

# Project Map

| Project                             | Focus                                               |
| ----------------------------------- | --------------------------------------------------- |
| RouteSentinel                       | BGP · RPKI · MRT · VRP · route security             |
| GeoFeed-Harvester                   | RFC8805 · GeoIP · geofeeds · RIR · BGP              |
| ASN-Signal-Graph                    | ASN · CIDR · infrastructure signals · Tor · VPN     |
| IP-Knowledge-Layer                  | ASN · enrichment · bot detection · VPN intelligence |
| GeoForge                            | GeoIP · MMDB · geolocation consensus · WHOIS        |
| MMDBForge                           | MaxMind DB · diffing · validation · tooling         |
| MMDB-WatchTower                     | MMDB operations · rollback · observability          |
| CrawlerScope                        | AI crawlers · scanners · monitoring probes          |
| Tor-Radar                           | Tor relay intelligence · Onionoo · dashboards       |
| PrefixCloak                         | privacy · anonymization · SIEM · telemetry          |
| blackroute                          | hostile infrastructure · reputation · MMDB          |
| VPN-Infrastructure-Intelligence-Lab | VPN infrastructure analytics · ASN visibility       |

---

# Collaboration

Open to collaboration around:

* IP intelligence datasets
* ASN and routing analytics
* VPN and Tor infrastructure research
* crawler and AI fetcher visibility
* GeoIP/MMDB quality engineering
* RPKI and BGP measurements
* fraud detection and SIEM enrichment

---

# Licensing

Licensing varies by repository depending on source constraints and redistribution requirements.

Most repositories use:

* Apache-2.0 or MIT for code
* CC0-1.0 for generated datasets

See repository license files for details.

