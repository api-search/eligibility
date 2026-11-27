---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to open an account.
    value: '18'
  restricted_uses:
  - summary: Competitive use
    text: 'Without our prior written consent, you may not: use the service to design, build, train or improve a competing search index, crawler, or search or retrieval API'
  - summary: Personal license limits
    text: Putting results in front of anyone but you — in a product, a service, a client deliverable, or a public website.
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
name: blopus-ai
provenance_date: '2026-11-09'
provider_name: blopus-ai
provider_slug: blopus-ai
slug: blopus-ai-eligibility
source_date: '2026-11-09'
source_filename: blopus-ai-eligibility.yml
source_heading: Eligibility
source_page: https://blopus.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: blopus-ai\naid: blopus-ai\nurl: https://blopus.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Competitive use\n  text: 'Without our prior written consent, you may not: use the service to design, build, train or improve a competing\n    search index, crawler, or search or retrieval API'\n- summary: Personal license limits\n  text: Putting results in front of anyone but you — in a product, a service, a client deliverable, or a public\n    website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to open an account.\n"
source_yaml_url: https://artifacts.apis.io/blopus-ai/eligibility/blopus-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from blopus-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Search
- MCP
---
