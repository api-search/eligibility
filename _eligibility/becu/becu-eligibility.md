---
claim_count: 1
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
  - summary: Wrongful or unlawful use of the Site
    text: will not use the Site or any information obtained from it for any wrongful, unauthorized or unlawful purpose
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
name: BECU
provenance_date: '2026-11-09'
provider_name: BECU
provider_slug: becu
slug: becu-eligibility
source_date: '2026-11-09'
source_filename: becu-eligibility.yml
source_heading: Eligibility
source_page: https://www.becu.org/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BECU\naid: becu\nurl: https://www.becu.org/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Wrongful or unlawful use of the Site\n  text: will not use the Site or any information obtained from it for any wrongful, unauthorized or unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/becu/eligibility/becu-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from BECU's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Credit Union
- Open Finance
- CFPB 1033
---
