---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old and using the Service for business purposes.
    value: '18'
  restricted_uses:
  - summary: Business purposes only
    text: You must be at least 18 years old and using the Service for business purposes.
  - summary: No harassment or fraud
    text: use the data to harass, discriminate against, defraud or deceive anyone
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You sign in with an emailed link or a supported third-party sign-in provider
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BuyerCue
provenance_date: '2026-11-09'
provider_name: BuyerCue
provider_slug: buyercue-io
slug: buyercue-io-eligibility
source_date: '2026-11-09'
source_filename: buyercue-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.buyercue.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuyerCue\naid: buyercue-io\nurl: https://www.buyercue.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Business purposes only\n  text: You must be at least 18 years old and using the Service for business purposes.\n- summary: No harassment or fraud\n  text: use the data to harass, discriminate against, defraud or deceive anyone\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You sign in with an emailed link or a supported third-party sign-in provider\nminimum_age:\n  value: '18'\n  text: You\
  \ must be at least 18 years old and using the Service for business purposes.\n"
source_yaml_url: https://artifacts.apis.io/buyercue-io/eligibility/buyercue-io-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from BuyerCue's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Software-as-a-Service
- Leads
- Buying Signals
- Growth
---
