---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: Canada Too Good To Go Canada Technology Ltd.
  minimum_age:
    text: You are the age of majority in your local jurisdiction.
    value: age of majority
  restricted_uses:
  - summary: Sanctioned persons or countries
    text: You’re not located in a sanctioned country or on a sanctioned persons list.
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
name: Too Good To Go
provenance_date: '2026-11-10'
provider_name: Too Good To Go
provider_slug: too-good-to-go
slug: too-good-to-go-eligibility
source_date: '2026-11-10'
source_filename: too-good-to-go-eligibility.yml
source_heading: Eligibility
source_page: https://www.toogoodtogo.com/en-gb/legal/terms-and-conditions-using-the-app
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Too Good To Go\naid: too-good-to-go\nurl: https://www.toogoodtogo.com/en-gb/legal/terms-and-conditions-using-the-app\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: Canada Too Good To Go Canada Technology Ltd.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned persons or countries\n  text: You’re not located in a sanctioned country or on a sanctioned persons list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: You are the age of majority in your local jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/too-good-to-go/eligibility/too-good-to-go-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Too Good To Go's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Food Waste
- Surplus Food
- Marketplace
- Sustainability
- Grocery Retail
- Consumer App
- Climate Tech
- B Corporation
- Denmark
---
