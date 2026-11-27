---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are at least 18 years of age and legally able to enter into a contract
    value: '18'
  restricted_uses:
  - summary: Stock Gift eligibility for charities
    text: 'the organization will need to meet the following eligibility requirements: (i) be recognized by the IRS as exempt from federal income taxation under Section 501(c)(3)'
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
name: FreeWill
provenance_date: '2026-11-09'
provider_name: FreeWill
provider_slug: freewill
slug: freewill-eligibility
source_date: '2026-11-09'
source_filename: freewill-eligibility.yml
source_heading: Eligibility
source_page: https://www.freewill.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FreeWill\naid: freewill\nurl: https://www.freewill.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Stock Gift eligibility for charities\n  text: 'the organization will need to meet the following eligibility requirements: (i) be recognized by the IRS\n    as exempt from federal income taxation under Section 501(c)(3)'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age and legally able to enter into a contract\n"
source_yaml_url: https://artifacts.apis.io/freewill/eligibility/freewill-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from FreeWill's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Estate Planning
- Wills
- Non-Profit
- Planned Giving
- Legal Tech
---
