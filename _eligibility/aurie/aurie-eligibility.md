---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 (eighteen) years of age before you can use this website.
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
name: Aurie
provenance_date: '2026-11-09'
provider_name: Aurie
provider_slug: aurie
slug: aurie-eligibility
source_date: '2026-11-09'
source_filename: aurie-eligibility.yml
source_heading: Eligibility
source_page: https://www.livewithaurie.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aurie\naid: aurie\nurl: https://www.livewithaurie.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 (eighteen) years of age before you can use this website.\n"
source_yaml_url: https://artifacts.apis.io/aurie/eligibility/aurie-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Aurie's own page on 2026-11-09.
synthetic: false
tags:
- Medical Devices
- Health Tech
- Catheter
- Reusable
- FDA
---
