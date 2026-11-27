---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This applies to US customers.
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
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
name: Lovepop
provenance_date: '2026-11-09'
provider_name: Lovepop
provider_slug: lovepop
slug: lovepop-eligibility
source_date: '2026-11-09'
source_filename: lovepop-eligibility.yml
source_heading: Eligibility
source_page: https://www.lovepop.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lovepop\naid: lovepop\nurl: https://www.lovepop.com/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This applies to US customers.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/lovepop/eligibility/lovepop-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Lovepop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Greeting Cards
- Gifting
- E-Commerce
- Retail
- Consumer Products
- Shopify
- Techstars
---
