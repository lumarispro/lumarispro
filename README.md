<p align="center">
  <a href="https://lumaris.space"><img src="https://raw.githubusercontent.com/lumarispro/lumarispro/main/media/banner.svg?v=1" width="100%" alt="Lumaris — Infrastructure, kept in steady light."></a>
</p>

<p align="center">
  <a href="https://lumaris.space"><b>lumaris.space</b></a> &nbsp;·&nbsp;
  <a href="mailto:lumarispro@gmail.com">lumarispro@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://discord.com/users/1035236848882159666">Discord</a>
</p>

Lumaris designs and operates the layer underneath your product: bare-metal cloud, platform automation and observability, run by engineers who treat uptime as a craft. Our own fleet of dedicated servers runs in European data centres.

## The stack

We think about infrastructure as layers, each one resting on the one below. Every layer has a repository: the tooling we use to run it ourselves, published as it is.

<a href="https://github.com/lumarispro/lava-provider"><img src="https://raw.githubusercontent.com/lumarispro/lumarispro/main/media/layer-04.svg?v=1" width="100%" alt="Layer 04 · Network nodes · lava-provider"></a>
<a href="https://github.com/lumarispro/grafana-dashboards"><img src="https://raw.githubusercontent.com/lumarispro/lumarispro/main/media/layer-03.svg?v=1" width="100%" alt="Layer 03 · Observability · lava-provider-exporter, grafana-dashboards"></a>
<a href="https://github.com/lumarispro/server-bootstrap"><img src="https://raw.githubusercontent.com/lumarispro/lumarispro/main/media/layer-02.svg?v=1" width="100%" alt="Layer 02 · Platform · server-bootstrap"></a>
<a href="https://github.com/lumarispro/lumaris.space"><img src="https://raw.githubusercontent.com/lumarispro/lumarispro/main/media/layer-01.svg?v=1" width="100%" alt="Layer 01 · Metal · lumaris.space"></a>

| Layer | Repository | What's inside |
|:-:|---|---|
| `04` | [lava-provider](https://github.com/lumarispro/lava-provider) | Install, service unit, TLS proxy and status scripts for our Lava RPC provider |
| `03` | [lava-provider-exporter](https://github.com/lumarispro/lava-provider-exporter) | Prometheus exporter for a provider's on-chain state: stake, delegations, jails, per spec |
| `03` | [grafana-dashboards](https://github.com/lumarispro/grafana-dashboards) | Dashboards and alert rules for hosts and the Lava provider |
| `02` | [server-bootstrap](https://github.com/lumarispro/server-bootstrap) | Ansible roles that turn a fresh bare-metal host into a hardened, monitored node |
| `01` | [lumaris.space](https://github.com/lumarispro/lumaris.space) | Source of our website |

## On public chains

Blockchain nodes are demanding infrastructure: they never stop syncing, and their performance is measured in public. We run them with the same hardware, automation and monitoring as everything else.

<a href="https://info.lavanet.xyz/provider/lava@15ngms6me8r486xs3nda0y6p2d56gym687etymg"><img src="https://raw.githubusercontent.com/lumarispro/lumarispro/main/media/lava.svg?v=1" width="100%" alt="Lumaris on Lava Network: RPC provider for 31 specs"></a>

## How we work

1. **Design for failure.** Redundancy where it matters, simplicity everywhere else.
2. **Automate the routine.** Provisioning, patching and recovery are code.
3. **Measure everything.** If it isn't observed, it isn't operated.

<p align="center"><sub>© 2026 Lumaris · Europe</sub></p>
