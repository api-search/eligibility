---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Matchory’s services are directed exclusively at entrepreneurs within the meaning of Section 14 of the German Civil Code (BGB).
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Business e-mail for accounts
    text: Only business e-mail addresses may be used to open an account.
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
name: Matchory
provenance_date: '2026-11-10'
provider_name: Matchory
provider_slug: matchory
slug: matchory-eligibility
source_date: '2026-11-10'
source_filename: matchory-eligibility.yml
source_heading: Eligibility
source_page: https://matchory.com/en/gtc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Matchory\naid: matchory\nurl: https://matchory.com/en/gtc\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Matchory’s services are directed exclusively at entrepreneurs within the meaning of Section 14 of the German\n    Civil Code (BGB).\nrestricted_uses:\n- summary: Business e-mail for accounts\n  text: Only business e-mail addresses may be used to open an account.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/matchory/eligibility/matchory-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Matchory's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Procurement
- Supplier Discovery
- Sourcing
- Supply Chain
- Data Enrichment
- Entity Resolution
- Market Intelligence
- Risk Management
- MCP
---
