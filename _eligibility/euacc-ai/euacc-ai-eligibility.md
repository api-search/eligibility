---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person, one company listing per account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited activities
    text: 'Don''t use EUACC to: — Scrape, crawl, or bulk-download data without permission.'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: When your startup listing is approved, the information you choose to publish becomes visible in the EUACC directory and available through our MCP.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EUACC
provenance_date: '2026-11-09'
provider_name: EUACC
provider_slug: euacc-ai
slug: euacc-ai-eligibility
source_date: '2026-11-09'
source_filename: euacc-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.euacc.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EUACC\naid: euacc-ai\nurl: https://www.euacc.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person, one company listing per account.\nrestricted_uses:\n- summary: Prohibited activities\n  text: 'Don''t use EUACC to: — Scrape, crawl, or bulk-download data without permission.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: When your startup listing is approved, the information you choose to publish becomes visible in the EUACC\n    directory and available through our MCP.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/euacc-ai/eligibility/euacc-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from EUACC's own page on 2026-11-09.
synthetic: false
tags:
- Funding
- Europe
- Tech
- Investor
- Innovation
---
