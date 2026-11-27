---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you (1) are over the age of 18
    type: individual
  - text: have the right and authority to legally bind yourself or your company, firm and/or employer to these Terms
    type: business
  minimum_age:
    text: you represent that you (1) are over the age of 18
    value: '18'
  restricted_uses:
  - summary: Competitors restricted
    text: If you are or become a direct competitor to us, you may not access or use the Services without our explicit, advance, written consent
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Any User submitting a payment may be required to submit additional information related to identity verification or anti-money laundering compliance.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DealMaker
provenance_date: '2026-11-09'
provider_name: DealMaker
provider_slug: dealmaker
slug: dealmaker-eligibility
source_date: '2026-11-09'
source_filename: dealmaker-eligibility.yml
source_heading: Eligibility
source_page: https://www.dealmaker.tech/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DealMaker\naid: dealmaker\nurl: https://www.dealmaker.tech/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you (1) are over the age of 18\n- type: business\n  text: have the right and authority to legally bind yourself or your company, firm and/or employer to these Terms\nrestricted_uses:\n- summary: Competitors restricted\n  text: If you are or become a direct competitor to us, you may not access or use the Services without our explicit,\n    advance, written consent\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: Any User submitting a payment may be required to submit additional information related to identity verification\n    or anti-money laundering compliance.\nminimum_age:\n  value: '18'\n  text: you represent that you (1) are over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/dealmaker/eligibility/dealmaker-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from DealMaker's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Capital Raising
- Investment Platform
- Software-as-a-Service
---
