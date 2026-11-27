---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: form a legal agreement between the legal entity on behalf of which you are acting (“ Customer ”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: Customer expressly agrees that it shall not, and shall cause its representatives to agree not to, export, directly or indirectly, re-export, divert, transfer or make available any part of Dremio Cloud
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
name: Dremio
provenance_date: '2026-11-09'
provider_name: Dremio
provider_slug: dremio
slug: dremio-eligibility
source_date: '2026-11-09'
source_filename: dremio-eligibility.yml
source_heading: Eligibility
source_page: https://www.dremio.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dremio\naid: dremio\nurl: https://www.dremio.com/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: form a legal agreement between the legal entity on behalf of which you are acting (“ Customer ”)\nrestricted_uses:\n- summary: Export control restrictions\n  text: Customer expressly agrees that it shall not, and shall cause its representatives to agree not to, export,\n    directly or indirectly, re-export, divert, transfer or make available any part of Dremio Cloud\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dremio/eligibility/dremio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dremio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Lakehouse
- Analytics
- SQL Query Engine
- Apache Iceberg
- Apache Arrow
- Data Catalog
- Semantic Layer
- AI Agents
- MCP
---
