# PingCAP

PingCAP is the company behind TiDB, an open-source, MySQL-compatible distributed SQL database built for hybrid
transactional and analytical processing (HTAP), horizontal scale-out, Raft-based strong consistency, and vector
search for AI workloads. PingCAP operates TiDB Cloud, the fully managed DBaaS delivered in Starter, Essential,
Premium, Dedicated, BYOC and Lake tiers across AWS, Google Cloud, Azure and Alibaba Cloud.

- Website: https://www.pingcap.com/
- Documentation: https://docs.pingcap.com/
- API overview: https://docs.pingcap.com/tidbcloud/api-overview/
- Status: https://status.tidbcloud.com/
- GitHub: https://github.com/pingcap and https://github.com/tidbcloud

## APIs in this repo

| API | Host | Spec |
|---|---|---|
| TiDB Cloud Starter and Essential (v1beta1) | serverless.tidbapi.com | Swagger 2.0 |
| TiDB Cloud Dedicated (v1beta1) | dedicated.tidbapi.com | Swagger 2.0 |
| TiDB Cloud IAM (v1beta1) | iam.tidbapi.com | Swagger 2.0 |
| TiDB Cloud Billing (v1beta1) | billing.tidbapi.com | Swagger 2.0 |
| TiDB Cloud Data Service (v1beta1) | dataservice.tidbapi.com | Swagger 2.0 |
| TiDB Cloud API (v1beta, legacy) | api.tidbcloud.com | Swagger 2.0 |
| TiDB Cloud Zero (v1alpha1) | zero.tidbapi.com | Swagger 2.0 |
| TiDB Data Migration (DM) | self-managed dm-master | OpenAPI 3.0.0 |
| OSS Insight Public API | api.ossinsight.io | OpenAPI 3.0.3 |

Plus the official TiDB MCP Server (stdio / SSE, shipped in `pytidb[mcp]`).

All specifications in `openapi/` were harvested verbatim from PingCAP's own hosts; all skills in `skills/` were
harvested verbatim from `pingcap/agent-rules` and `tidbcloud/skills`.
