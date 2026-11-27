---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - TW
    text: 本公司直售/代理（台灣在地出貨）
  minimum_age:
    text: 若您為未滿十八歲，您應於您的法定代理人（或監護人）同意之情形下，始得透過本平台進行購買。
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
name: Citiesocial
provenance_date: '2026-11-09'
provider_name: Citiesocial
provider_slug: citiesocial
slug: citiesocial-eligibility
source_date: '2026-11-09'
source_filename: citiesocial-eligibility.yml
source_heading: Eligibility
source_page: https://www.citiesocial.com/pages/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Citiesocial\naid: citiesocial\nurl: https://www.citiesocial.com/pages/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - TW\n  excluded: []\n  text: 本公司直售/代理（台灣在地出貨）\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 若您為未滿十八歲，您應於您的法定代理人（或監護人）同意之情形下，始得透過本平台進行購買。\n"
source_yaml_url: https://artifacts.apis.io/citiesocial/eligibility/citiesocial-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Citiesocial's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Marketplace
- Curated
- Taiwan
- Cross-Border
---
