---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Products and services may vary by jurisdiction; certain products are not available to all users.
  entity_types:
  - text: we authorize your use of the Site only for individual, consumer purposes
    type: individual
  minimum_age:
    text: By using the Site, you agree that you are at least 18 years of age, or if you are under 18 years of age (a “Minor”), that you are using the Site with the consent of your parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Individual consumer use only
    text: we authorize your use of the Site only for individual, consumer purposes (“Permitted Purposes”)
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
name: Ledgebrook
provenance_date: '2026-11-09'
provider_name: Ledgebrook
provider_slug: ledgebrook
slug: ledgebrook-eligibility
source_date: '2026-11-09'
source_filename: ledgebrook-eligibility.yml
source_heading: Eligibility
source_page: https://www.ledgebrook.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ledgebrook\naid: ledgebrook\nurl: https://www.ledgebrook.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Products and services may vary by jurisdiction; certain products are not available to all users.\nentity_types:\n- type: individual\n  text: we authorize your use of the Site only for individual, consumer purposes\nrestricted_uses:\n- summary: Individual consumer use only\n  text: we authorize your use of the Site only for individual, consumer purposes (“Permitted Purposes”)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: By using the Site, you agree that you are at least 18 years of age, or if you are under 18 years of age\n    (a “Minor”), that you are using the Site with the consent of your parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/ledgebrook/eligibility/ledgebrook-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ledgebrook's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Excess and Surplus
- Specialty Insurance
- Managing General Agent
- Reinsurance
- Commercial Liability
- Cyber Insurance
- Underwriting
---
