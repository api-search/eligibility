---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - HK
    text: We provide the Services via this Website to persons in Hong Kong.
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
name: WeLab
provenance_date: '2026-11-10'
provider_name: WeLab
provider_slug: welab
slug: welab-eligibility
source_date: '2026-11-10'
source_filename: welab-eligibility.yml
source_heading: Eligibility
source_page: https://www.welab.bank/en/legal/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WeLab\naid: welab\nurl: https://www.welab.bank/en/legal/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - HK\n  excluded: []\n  text: We provide the Services via this Website to persons in Hong Kong.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/welab/eligibility/welab-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from WeLab's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Digital Banking
- virtual-bank
- Open Banking
- Hong Kong
- Indonesia
- Consumer Lending
- Payments
- hkma-open-api
- Financial Services
---
