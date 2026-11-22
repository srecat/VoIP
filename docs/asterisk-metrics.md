# Asterisk Metrics Reference

Key metrics collected by `asterisk_exporter` and monitored in Grafana.

## Calls & Channels
- `asterisk_core_active_calls`: Number of currently active calls.
- `asterisk_core_active_channels`: Number of currently active channels.
- `asterisk_core_processed_calls`: Total number of processed calls.

## System Health
- `asterisk_core_system_uptime_seconds`: Time since Asterisk startup.
- `asterisk_core_system_memory_free_bytes`: Free memory in bytes.
- `asterisk_core_tasks_processes_in_queue`: Tasks in queue (indicates load).

## SIP
- `asterisk_sip_current_qualified`: Number of registered SIP endpoints.
- `asterisk_sip_active_channels`: Number of active SIP channels.
