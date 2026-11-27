---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - AT
    - DE
    - IE
    text: Bloom & Wild only delivers within the United Kingdom, Austria, Germany and Ireland.
  minimum_age:
    text: By placing an order for alcohol, you confirm that you and the recipient are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Alcohol purchases by under-18s
    text: It is a criminal offence for a person under 18 to purchase or attempt to purchase alcohol.
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
name: Bloom & Wild
provenance_date: '2026-11-09'
provider_name: Bloom & Wild
provider_slug: bloom--wild
slug: bloom--wild-eligibility
source_date: '2026-11-09'
source_filename: bloom--wild-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomandwild.com/terms-and-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloom & Wild\naid: bloom--wild\nurl: https://www.bloomandwild.com/terms-and-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - AT\n  - DE\n  - IE\n  excluded: []\n  text: Bloom & Wild only delivers within the United Kingdom, Austria, Germany and Ireland.\nentity_types: []\nrestricted_uses:\n- summary: Alcohol purchases by under-18s\n  text: It is a criminal offence for a person under 18 to purchase or attempt to purchase alcohol.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By placing an order for alcohol, you confirm\
  \ that you and the recipient are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/bloom--wild/eligibility/bloom--wild-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bloom & Wild's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Flowers
- Gifting
- Direct to Consumer
- Subscription
- Consumer Goods
- Logistics
- United Kingdom
- B Corp
---
