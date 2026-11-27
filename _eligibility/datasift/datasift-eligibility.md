---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Program is available to United States residents with a U.S. mobile phone number, age 18 or older
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
name: Datasift
provenance_date: '2026-11-09'
provider_name: Datasift
provider_slug: datasift
slug: datasift-eligibility
source_date: '2026-11-09'
source_filename: datasift-eligibility.yml
source_heading: Eligibility
source_page: https://www.datasift.ai/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Datasift\naid: datasift\nurl: https://www.datasift.ai/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Program is available to United States residents with a U.S. mobile phone number, age 18 or older\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datasift/eligibility/datasift-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Datasift's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Data Platform
- Marketing
- Analytics
---
