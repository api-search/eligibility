---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is higher) to create an account or use our services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is higher) to create an account or use our services.
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
name: Blocsmith
provenance_date: '2026-11-09'
provider_name: Blocsmith
provider_slug: blocsmith-io
slug: blocsmith-io-eligibility
source_date: '2026-11-09'
source_filename: blocsmith-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.blocsmith.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blocsmith\naid: blocsmith-io\nurl: https://www.blocsmith.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is higher)\n    to create an account or use our services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is higher)\n    to create an account or\
  \ use our services.\n"
source_yaml_url: https://artifacts.apis.io/blocsmith-io/eligibility/blocsmith-io-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Blocsmith's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Website Builder
- No-Code
- Software-as-a-Service
- Automation
---
