---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Website is offered and available to users who reside in the United States or any of its territories or possessions.
  minimum_age:
    text: you represent and warrant that you are of legal age to form a binding contract with the Company
    value: legal age
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website(s) only for lawful purposes and in accordance with these Terms of Use.
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
name: PayTrace
provenance_date: '2026-11-10'
provider_name: PayTrace
provider_slug: paytrace
slug: paytrace-eligibility
source_date: '2026-11-10'
source_filename: paytrace-eligibility.yml
source_heading: Eligibility
source_page: https://paytrace.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayTrace\naid: paytrace\nurl: https://paytrace.net/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Website is offered and available to users who reside in the United States or any of its territories\n    or possessions.\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Website(s) only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you represent and warrant that you are of legal age\
  \ to form a binding contract with the Company\n"
source_yaml_url: https://artifacts.apis.io/paytrace/eligibility/paytrace-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PayTrace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Merchant Services
---
