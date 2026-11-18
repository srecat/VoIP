# VoIP Observability Stack

Infrastructure-as-Code homelab for monitoring a VoIP PBX (Asterisk)
and network equipment (MikroTik) with Prometheus, Grafana, Loki and Alertmanager.

**Stack:** Proxmox · Ubuntu 22.04 · Ansible · Asterisk (PJSIP) · MikroTik (SNMP)
· Prometheus · Alertmanager · Grafana · Loki · Promtail · GitHub Actions.

## Status

🚧 Work in progress — documentation and deployment roles are being built.

## Documentation

See [`docs/index.md`](docs/index.md) (coming soon).

## Implemented Features

- ✅ **Infrastructure as Code:** Ansible roles for Node Exporter, Asterisk, Prometheus, Grafana.
- ✅ **VoIP:** Asterisk PBX with PJSIP (extensions 1001-1003) and Echo Test.
- ✅ **Monitoring:** Prometheus with node_exporter targets (2/2 UP).
- ✅ **Visualization:** Grafana with provisioned Prometheus datasource.

Prometheus Targets - docs/screenshots/prometheus-targets.png


## License

MIT
