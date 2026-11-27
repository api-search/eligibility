---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Cleancult makes no representation that the Service is appropriate, lawful or available in other locations.
  minimum_age:
    text: Individuals under the age of majority in the jurisdiction in which they are located may not use the Service.
    value: age of majority
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You agree not to use the Service for any other purpose
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: In certain instances Cleancult or its vendors may require you to provide proof of identity to access or use the Service
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cleancult
provenance_date: '2026-11-09'
provider_name: Cleancult
provider_slug: cleancult
slug: cleancult-eligibility
source_date: '2026-11-09'
source_filename: cleancult-eligibility.yml
source_heading: Eligibility
source_page: https://www.cleancult.com/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleancult\naid: cleancult\nurl: https://www.cleancult.com/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Cleancult makes no representation that the Service is appropriate, lawful or available in other locations.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You agree not to use the Service for any other purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: In certain instances Cleancult or its vendors may require you to provide proof of identity to access or\n    use the Service\n\
  minimum_age:\n  value: age of majority\n  text: Individuals under the age of majority in the jurisdiction in which they are located may not use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cleancult/eligibility/cleancult-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cleancult's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sustainability
- Cleaning
- Eco-friendly
- Subscription
---
