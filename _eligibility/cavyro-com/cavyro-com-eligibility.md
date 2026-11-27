---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Cold outreach and bulk messaging
    text: send bulk or automated messages to people who have no prior conversation with you (cold outreach, scraped lists, purchased lists)
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
name: Cavyro
provenance_date: '2026-11-09'
provider_name: Cavyro
provider_slug: cavyro-com
slug: cavyro-com-eligibility
source_date: '2026-11-09'
source_filename: cavyro-com-eligibility.yml
source_heading: Eligibility
source_page: https://cavyro.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cavyro\naid: cavyro-com\nurl: https://cavyro.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Cold outreach and bulk messaging\n  text: send bulk or automated messages to people who have no prior conversation with you (cold outreach, scraped\n    lists, purchased lists)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cavyro-com/eligibility/cavyro-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Cavyro's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Telegram
- Sales
- Automation
- MCP
---
