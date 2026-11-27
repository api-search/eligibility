---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To use our Service, you must: Be at least 18 years old'
    type: individual
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Prohibited uses
    text: Engage in any illegal, fraudulent, or deceptive practices
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
name: Bavlio
provenance_date: '2026-11-09'
provider_name: Bavlio
provider_slug: bavlio-com
slug: bavlio-com-eligibility
source_date: '2026-11-09'
source_filename: bavlio-com-eligibility.yml
source_heading: Eligibility
source_page: https://bavlio.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bavlio\naid: bavlio-com\nurl: https://bavlio.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To use our Service, you must: Be at least 18 years old'\nrestricted_uses:\n- summary: Prohibited uses\n  text: Engage in any illegal, fraudulent, or deceptive practices\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/bavlio-com/eligibility/bavlio-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bavlio's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Sales
- Outreach
- Automation
- Lead Generation
- Company
---
