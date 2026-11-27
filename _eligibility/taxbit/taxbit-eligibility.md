---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
  entity_types:
  - text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
    type: individual
  minimum_age:
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
    value: '18'
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
name: TaxBit
provenance_date: '2026-11-10'
provider_name: TaxBit
provider_slug: taxbit
slug: taxbit-eligibility
source_date: '2026-11-10'
source_filename: taxbit-eligibility.yml
source_heading: Eligibility
source_page: https://www.taxbit.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TaxBit\naid: taxbit\nurl: https://www.taxbit.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and\
  \ reside in the United States or any of its territories to use the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/taxbit/eligibility/taxbit-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from TaxBit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tax
- Tax Compliance
- Information Reporting
- Digital Assets
- Cryptocurrency
- Accounting
- RegTech
---
