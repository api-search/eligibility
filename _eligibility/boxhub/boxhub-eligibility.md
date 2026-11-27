---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Limited Warranty applies to equipment shipped to the mainland of a State within the United States, excluding Hawaii and Alaska; Canadian customers covered by Section 23.
  minimum_age:
    text: null
    value: null
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
name: Boxhub
provenance_date: '2026-11-09'
provider_name: Boxhub
provider_slug: boxhub
slug: boxhub-eligibility
source_date: '2026-11-09'
source_filename: boxhub-eligibility.yml
source_heading: Eligibility
source_page: https://boxhub.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boxhub\naid: boxhub\nurl: https://boxhub.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Limited Warranty applies to equipment shipped to the mainland of a State within the United States, excluding\n    Hawaii and Alaska; Canadian customers covered by Section 23.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boxhub/eligibility/boxhub-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Boxhub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Shipping
- Containers
- Logistics
- E-Commerce
---
