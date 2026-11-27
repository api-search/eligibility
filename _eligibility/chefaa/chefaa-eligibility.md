---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - EG
    text: Order medicines online from pharmacies in Egypt
  entity_types:
  - text: the person who downloads or uses the application or the entity represented by the person on behalf
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial personal data collection
    text: Not to collect any personal information for commercial purposes, including full name, address, and e-mail.
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
name: Chefaa
provenance_date: '2026-11-09'
provider_name: Chefaa
provider_slug: chefaa
slug: chefaa-eligibility
source_date: '2026-11-09'
source_filename: chefaa-eligibility.yml
source_heading: Eligibility
source_page: https://chefaa.com/eg-en/page/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chefaa\naid: chefaa\nurl: https://chefaa.com/eg-en/page/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EG\n  excluded: []\n  text: Order medicines online from pharmacies in Egypt\nentity_types:\n- type: individual\n  text: the person who downloads or uses the application or the entity represented by the person on behalf\nrestricted_uses:\n- summary: No commercial personal data collection\n  text: Not to collect any personal information for commercial purposes, including full name, address, and e-mail.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chefaa/eligibility/chefaa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Chefaa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pharmacy
- Healthcare
- Digital Health
- Pharmacy Benefits
- E-Commerce
- Delivery
- Egypt
- Middle East
---
