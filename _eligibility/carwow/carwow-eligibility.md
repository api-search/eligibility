---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - DE
    - ES
    text: We make this site available for United Kingdom residents over the age of 18 only. We have sites in Germany and Spain available to residents of those countries.
  entity_types:
  - text: We make this site available for United Kingdom residents over the age of 18 only.
    type: individual
  - text: If you are using our Sites on behalf of a business, that business accepts these Terms and Conditions.
    type: business
  minimum_age:
    text: We make this site available for United Kingdom residents over the age of 18 only.
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: we only provide our sites for domestic and private use.
  - summary: Ask Mat non-commercial use
    text: You may use Ask Mat for your personal and non-commercial purposes only.
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
name: Carwow
provenance_date: '2026-11-09'
provider_name: Carwow
provider_slug: carwow
slug: carwow-eligibility
source_date: '2026-11-09'
source_filename: carwow-eligibility.yml
source_heading: Eligibility
source_page: https://www.carwow.co.uk/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carwow\naid: carwow\nurl: https://www.carwow.co.uk/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - DE\n  - ES\n  excluded: []\n  text: We make this site available for United Kingdom residents over the age of 18 only. We have sites in Germany\n    and Spain available to residents of those countries.\nentity_types:\n- type: individual\n  text: We make this site available for United Kingdom residents over the age of 18 only.\n- type: business\n  text: If you are using our Sites on behalf of a business, that business accepts these Terms and Conditions.\nrestricted_uses:\n- summary:\
  \ Domestic and private use only\n  text: we only provide our sites for domestic and private use.\n- summary: Ask Mat non-commercial use\n  text: You may use Ask Mat for your personal and non-commercial purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We make this site available for United Kingdom residents over the age of 18 only.\n"
source_yaml_url: https://artifacts.apis.io/carwow/eligibility/carwow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Carwow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Automotive
- Marketplace
- Car Buying
- Car Selling
- Leasing
- Electric Vehicles
- United Kingdom
---
