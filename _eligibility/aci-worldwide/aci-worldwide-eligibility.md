---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the Site, you represent that you are at least 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Under-18 users
    text: If you are under 18 years old, you may use the Site only with the involvement and approval of a parent or guardian.
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
name: ACI Worldwide
provenance_date: '2026-11-09'
provider_name: ACI Worldwide
provider_slug: aci-worldwide
slug: aci-worldwide-eligibility
source_date: '2026-11-09'
source_filename: aci-worldwide-eligibility.yml
source_heading: Eligibility
source_page: https://www.aciworldwide.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ACI Worldwide\naid: aci-worldwide\nurl: https://www.aciworldwide.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Under-18 users\n  text: If you are under 18 years old, you may use the Site only with the involvement and approval of a parent or\n    guardian.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Site, you represent that you are at least 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/aci-worldwide/eligibility/aci-worldwide-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from ACI Worldwide's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- United States
- Payment Gateway
- Payment Processing
- Acquiring
- Card Payments
- E-Commerce
- Fraud Prevention
- Tokenization
- 3D Secure
- Bill Payments
- Real-Time Payments
- ISO 20022
---
