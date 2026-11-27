---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that You are authorized to agree to the Terms on behalf of yourself and each such entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Developing products based on MSCI materials
    text: 'Unless expressly authorized by MSCI in an applicable Order Form, Client and its Affiliates shall not use, and shall not permit any third party to use: (i) any MSCI Proprietary Materials in connection with Developing or Offering any MSCI-Related Product'
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
name: MSCI
provenance_date: '2026-11-10'
provider_name: MSCI
provider_slug: msci
slug: msci-eligibility
source_date: '2026-11-10'
source_filename: msci-eligibility.yml
source_heading: Eligibility
source_page: https://www.msci.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MSCI\naid: msci\nurl: https://www.msci.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You represent and warrant that You are authorized to agree to the Terms on behalf of yourself and each such\n    entity.\nrestricted_uses:\n- summary: Developing products based on MSCI materials\n  text: 'Unless expressly authorized by MSCI in an applicable Order Form, Client and its Affiliates shall not use,\n    and shall not permit any third party to use: (i) any MSCI Proprietary Materials in connection with Developing\n \
  \   or Offering any MSCI-Related Product'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/msci/eligibility/msci-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from MSCI's own page on 2026-11-10.
synthetic: false
tags:
- Financial Data
- Index
- ESG
- Climate
- Risk Analytics
- Real Estate
- Private Assets
- Investing
---
