# Hi, I'm Paul 👋

Broadband / network engineer who automates the tedious parts of the job, and runs a
homelab to break things before production does.

## What I focus on

- **Network automation** — Ansible against Cisco IOS / IOS-XE and DOCSIS CMTS platforms
- **Infrastructure & ops** — Proxmox, Docker, self-hosted GitLab, Semaphore (Ansible CI), NetBox (IPAM/DCIM)
- **Secrets & security** — HashiCorp Vault (AppRole, scoped policies), least-privilege by default
- **Monitoring** — Prometheus, SNMP, custom metric exporters
- **Python tooling** — data pipelines, scrapers, and a few local-LLM experiments
- **Custom AI tooling** - codebase prep, custom mcp, rag, plugins, & even custom harness creation (Most of these are private at the moment)

## Featured projects
- **[Devops](https://github.com/grafman56/devops-public)** - Devops tools & templates - Kubernetes, Ansible, Terraform, Hashicorp Packer
- **[Containerlabs](https://github.com/grafman56/containerlab-labs-public)** - Containerlab Enterprise Level Labs. BGP, SDWAN, DOCSIS CIN, Fabric, EVPN, Wireless w/ Radius
- **[scmsansible](https://github.com/grafman56/scmsansible)** — parallel CMTS cable-modem-count poller. An external CSV becomes a dynamic inventory, every CMTS polls concurrently, and one timestamped CSV report comes out. Unreachable devices are flagged instead of failing the run.
- **[ansibletestlocal](https://github.com/grafman56/ansibletestlocal)** — a clean, documented starter for checking Cisco IOS interfaces over SSH with Ansible (raw CLI + structured facts).
- **[docsismonitor](https://github.com/grafman56/docsismonitor)** — async SNMP to Prometheus exporter for CMTS downstream/upstream utilization and CPU.
- **[Ansible_Interface_Compare](https://github.com/grafman56/Ansible_Interface_Compare)** — snapshot interface packet counters and compare them over time (fact-cache and file-persistence approaches).
- **[WeissWave](https://github.com/grafman56/WeissWavePub)** — Python S&P 500 screener and backtester built on Weis Wave volume analysis, with multi-timeframe signals and a portfolio simulator.
- **[MTG-Tools](https://github.com/grafman56/mtg-tools)** — Magic card deck building assistant with built in theme detection and card strength

## Homelab

A self-hosted lab I use as a proving ground: virtualization, containerized services,
secrets management, config automation, and monitoring. The same tools I use at work,
run end to end so I actually understand them.

## Reach me

- https://www.linkedin.com/in/pauleiteliv/
- paul@paulsgarageva.com
