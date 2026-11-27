---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This MinIO AIStor Free Tier License Agreement (“ Agreement ”) between you (either an individual or an entity)
    type: individual
  - text: This MinIO AIStor Free Tier License Agreement (“ Agreement ”) between you (either an individual or an entity)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Standalone single-node only
    text: install and use the Software solely in standalone mode (single-node deployments without distributed clustering or high availability)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: MinIO
provenance_date: '2026-11-10'
provider_name: MinIO
provider_slug: minio
slug: minio-eligibility
source_date: '2026-11-10'
source_filename: minio-eligibility.yml
source_heading: Eligibility
source_page: https://www.min.io/legal/aistor-free-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MinIO\naid: minio\nurl: https://www.min.io/legal/aistor-free-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This MinIO AIStor Free Tier License Agreement (“ Agreement ”) between you (either an individual or an entity)\n- type: business\n  text: This MinIO AIStor Free Tier License Agreement (“ Agreement ”) between you (either an individual or an entity)\nrestricted_uses:\n- summary: Standalone single-node only\n  text: install and use the Software solely in standalone mode (single-node deployments without distributed clustering\n\
  \    or high availability)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/minio/eligibility/minio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from MinIO's own page on 2026-11-10.
synthetic: false
tags:
- Object Storage
- Storage
- S3 Compatible
- Cloud-Native
- Kubernetes
- Data Infrastructure
- AI Storage
- Company
---
