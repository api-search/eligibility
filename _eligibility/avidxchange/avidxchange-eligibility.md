---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You also represent and warrant that you are at least 18 years of age and are otherwise competent to be legally bound by the Website Agreement.
    type: individual
  minimum_age:
    text: You also represent and warrant that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: engage in any unlawful or illegal behavior
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
name: AvidXchange
provenance_date: '2026-11-09'
provider_name: AvidXchange
provider_slug: avidxchange
slug: avidxchange-eligibility
source_date: '2026-11-09'
source_filename: avidxchange-eligibility.yml
source_heading: Eligibility
source_page: https://www.avidxchange.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AvidXchange\naid: avidxchange\nurl: https://www.avidxchange.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You also represent and warrant that you are at least 18 years of age and are otherwise competent to be legally\n    bound by the Website Agreement.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: engage in any unlawful or illegal behavior\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You also represent and warrant that you\
  \ are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/avidxchange/eligibility/avidxchange-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AvidXchange's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounts Payable
- Payments
- Invoice Automation
- AP Automation
- B2B Payments
- Financial Operations
---
