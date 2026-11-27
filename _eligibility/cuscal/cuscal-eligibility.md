---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with applicable laws
    text: use the Services or Software other than in accordance with these Terms and in compliance with all applicable laws and regulations
  - source: https://www.cuscal.com/website-terms-of-use/
    summary: Unlawful purposes
    text: or use the Website for any other unlawful purpose or activity.
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
name: Cuscal
provenance_date: '2026-11-09'
provider_name: Cuscal
provider_slug: cuscal
slug: cuscal-eligibility
source_date: '2026-11-09'
source_filename: cuscal-eligibility.yml
source_heading: Eligibility
source_page: https://www.cuscal.com.au/cuscal-developer-hub-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cuscal\naid: cuscal\nurl: https://www.cuscal.com.au/cuscal-developer-hub-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.cuscal.com.au/cuscal-developer-hub-terms-and-conditions\n  - https://www.cuscal.com/website-terms-of-use/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Compliance with applicable laws\n  text: use the Services or Software other than in accordance with these Terms and in compliance with all applicable\n    laws and regulations\n- summary: Unlawful purposes\n  text: or use the Website for any other unlawful\
  \ purpose or activity.\n  source: https://www.cuscal.com/website-terms-of-use/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cuscal/eligibility/cuscal-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Cuscal's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Australia
- Card Issuing
- Issuer Processor
- Real-Time Payments
- Acquiring
- Open Banking
- Consumer Data Right
- Account-to-Account
- Fraud Prevention
- Banking as a Service
---
