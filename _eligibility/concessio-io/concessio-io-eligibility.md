---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is designed for professional use by infrastructure investment firms, advisory practices, and related institutional users.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive intelligence use
    text: We reserve the right to suspend or terminate accounts that violate these Terms, are used for competitive intelligence gathering against Concessio, or engage in systematic data extraction beyond normal platform usage.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Access to the Service requires an account created through our invitation process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Concessio
provenance_date: '2026-11-09'
provider_name: Concessio
provider_slug: concessio-io
slug: concessio-io-eligibility
source_date: '2026-11-09'
source_filename: concessio-io-eligibility.yml
source_heading: Eligibility
source_page: https://concessio.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Concessio\naid: concessio-io\nurl: https://concessio.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is designed for professional use by infrastructure investment firms, advisory practices, and\n    related institutional users.\nrestricted_uses:\n- summary: Competitive intelligence use\n  text: We reserve the right to suspend or terminate accounts that violate these Terms, are used for competitive\n    intelligence gathering against Concessio, or engage in systematic data extraction beyond normal platform usage.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Access to the Service requires an account created through our invitation process.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/concessio-io/eligibility/concessio-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Concessio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- Concessions
- Investment Intelligence
- Financial Data
- Project Finance
- MCP
---
