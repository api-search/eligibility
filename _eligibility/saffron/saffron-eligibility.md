---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: enables companies (“Customers”) to evaluate engineering candidates.
    type: business
  - text: 'By participating in an assessment on the Saffron platform, candidates acknowledge and agree that:'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No discrimination against candidates
    text: Not use the Service to discriminate against candidates on the basis of any protected characteristic
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
name: Saffron
provenance_date: '2026-11-10'
provider_name: Saffron
provider_slug: saffron
slug: saffron-eligibility
source_date: '2026-11-10'
source_filename: saffron-eligibility.yml
source_heading: Eligibility
source_page: https://www.trysaffron.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Saffron\naid: saffron\nurl: https://www.trysaffron.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: enables companies (“Customers”) to evaluate engineering candidates.\n- type: individual\n  text: 'By participating in an assessment on the Saffron platform, candidates acknowledge and agree that:'\nrestricted_uses:\n- summary: No discrimination against candidates\n  text: Not use the Service to discriminate against candidates on the basis of any protected characteristic\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/saffron/eligibility/saffron-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Saffron's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hiring
- Technical Assessment
- Recruiting
- Artificial Intelligence
- Developer Tools
- Y Combinator
---
