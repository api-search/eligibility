---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Where you enter into this Agreement on behalf of a company or other organization, you represent and warrant that you have authority to act on behalf of that entity and to bind that entity to this Agreement.
    type: business
  minimum_age:
    text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which you reside
    value: '18'
  restricted_uses:
  - summary: Journalistic, investigative, or unlawful purpose disclosure
    text: including without limitation, if you are using or will or intend to use the Services for any journalistic, investigative, or unlawful purpose.
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
name: Siteline
provenance_date: '2026-11-10'
provider_name: Siteline
provider_slug: siteline
slug: siteline-eligibility
source_date: '2026-11-10'
source_filename: siteline-eligibility.yml
source_heading: Eligibility
source_page: https://www.siteline.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Siteline\naid: siteline\nurl: https://www.siteline.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Where you enter into this Agreement on behalf of a company or other organization, you represent and warrant\n    that you have authority to act on behalf of that entity and to bind that entity to this Agreement.\nrestricted_uses:\n- summary: Journalistic, investigative, or unlawful purpose disclosure\n  text: including without limitation, if you are using or will or intend to use the Services for any journalistic,\n    investigative,\
  \ or unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older or are at least of the legally required age in the jurisdiction in which\n    you reside\n"
source_yaml_url: https://artifacts.apis.io/siteline/eligibility/siteline-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Siteline's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Construction
- Billing
- Payments
- Accounts Receivable
- Subcontractors
- Lien Waivers
- Compliance
- Construction Fintech
- Software-as-a-Service
---
