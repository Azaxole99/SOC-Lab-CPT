# SOC Architecture

```text
Internet
    │
    ▼
Firewall
    │
    ▼
Endpoints
(Windows/Linux)
    │
    ▼
Sysmon Logs
    │
    ▼
Wazuh Agent
    │
    ▼
Wazuh Manager
    │
    ▼
Elasticsearch
    │
    ▼
Kibana Dashboard
    │
    ▼
SOC Analyst
