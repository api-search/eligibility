---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer confirms it is not a resident or citizen of any country currently embargoed by the U.S. (Section 12.9).
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited content and unlawful use
    text: send or store infringing, obscene, threatening, libelous, or otherwise unlawful or tortious material
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
name: Sourceday
provenance_date: '2026-11-10'
provider_name: Sourceday
provider_slug: sourceday
slug: sourceday-eligibility
source_date: '2026-11-10'
source_filename: sourceday-eligibility.yml
source_heading: Eligibility
source_page: https://sourceday.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sourceday\naid: sourceday\nurl: https://sourceday.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer confirms it is not a resident or citizen of any country currently embargoed by the U.S. (Section\n    12.9).\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content and unlawful use\n  text: send or store infringing, obscene, threatening, libelous, or otherwise unlawful or tortious material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sourceday/eligibility/sourceday-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Sourceday's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Supply Chain
- Purchase Orders
- Supplier Management
- Procurement
- ERP Integration
- Manufacturing
- Software-as-a-Service
---
