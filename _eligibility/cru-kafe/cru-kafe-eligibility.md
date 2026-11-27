---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Orders can only be delivered to addresses within the United Kingdom (including Northern Ireland); this excludes PO Box addresses and BFPO addresses.
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We may refuse any application to join our website or receive our services for any reason whatsoever.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CRU Kafe
provenance_date: '2026-11-09'
provider_name: CRU Kafe
provider_slug: cru-kafe
slug: cru-kafe-eligibility
source_date: '2026-11-09'
source_filename: cru-kafe-eligibility.yml
source_heading: Eligibility
source_page: https://www.crukafe.com/en-us/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CRU Kafe\naid: cru-kafe\nurl: https://www.crukafe.com/en-us/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Orders can only be delivered to addresses within the United Kingdom (including Northern Ireland); this excludes\n    PO Box addresses and BFPO addresses.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We may refuse any application to join our website or receive our services for any reason whatsoever.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cru-kafe/eligibility/cru-kafe-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from CRU Kafe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coffee
- E-Commerce
- Retail
- Consumer Goods
- Food and Beverage
- Shopify
- Agentic Commerce
- Universal Commerce Protocol
---
