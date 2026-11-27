---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is built for professional use. It is open to consumers all the same, and every section below applies to a consumer in full
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or unauthorized uploads
    text: upload content that is unlawful where you are or where we operate; upload content you have no right to upload
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You can start without an account, and creating one keeps what you have already uploaded.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: docs2mcp-com
provenance_date: '2026-11-09'
provider_name: docs2mcp-com
provider_slug: docs2mcp-com
slug: docs2mcp-com-eligibility
source_date: '2026-11-09'
source_filename: docs2mcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://docs2mcp.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: docs2mcp-com\naid: docs2mcp-com\nurl: https://docs2mcp.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The service is built for professional use. It is open to consumers all the same, and every section below\n    applies to a consumer in full\nrestricted_uses:\n- summary: Unlawful or unauthorized uploads\n  text: upload content that is unlawful where you are or where we operate; upload content you have no right to upload\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: You can start without an\
  \ account, and creating one keeps what you have already uploaded.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/docs2mcp-com/eligibility/docs2mcp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from docs2mcp-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Document Management
- MCP
- Integration
- Cloud
---
