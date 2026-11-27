---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 to create an account.
    value: '13'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: Don't use Revnu to send spam, harass anyone, build illegal products, or violate the terms of the platforms it integrates with
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
name: Revnu
provenance_date: '2026-11-10'
provider_name: Revnu
provider_slug: revnu
slug: revnu-eligibility
source_date: '2026-11-10'
source_filename: revnu-eligibility.yml
source_heading: Eligibility
source_page: https://revnu.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revnu\naid: revnu\nurl: https://revnu.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Don't use Revnu to send spam, harass anyone, build illegal products, or violate the terms of the platforms\n    it integrates with\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 to create an account.\n"
source_yaml_url: https://artifacts.apis.io/revnu/eligibility/revnu-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Revnu's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Growth Automation
- Marketing
- Artificial Intelligence
- Software-as-a-Service
- Startups
- Lead Generation
- SEO
- MCP
- Agents
- Commerce
- A/B Testing
---
