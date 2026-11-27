---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - CA
    - GB
    - US
    text: Below are all the countries we currently ship to. If your country is not listed, we are not able to ship there currently.
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
name: Maelyscosmetics
provenance_date: '2026-11-10'
provider_name: Maelyscosmetics
provider_slug: maelyscosmetics
slug: maelyscosmetics-eligibility
source_date: '2026-11-10'
source_filename: maelyscosmetics-eligibility.yml
source_heading: Eligibility
source_page: https://www.maelyscosmetics.com/catalog
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maelyscosmetics\naid: maelyscosmetics\nurl: https://www.maelyscosmetics.com/catalog\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  - CA\n  - GB\n  - US\n  excluded: []\n  text: Below are all the countries we currently ship to. If your country is not listed, we are not able to ship\n    there currently.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/maelyscosmetics/eligibility/maelyscosmetics-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Maelyscosmetics's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cosmetics
- Beauty
- Body Care
- E-Commerce
- Direct to Consumer
- Skincare
---
