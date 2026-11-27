---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old or the age of majority in your jurisdiction to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old or the age of majority in your jurisdiction to use our Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful, disruptive, or harmful use
    text: Use the Services for any unlawful purpose.
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
name: Asato
provenance_date: '2026-11-09'
provider_name: Asato
provider_slug: asato
slug: asato-eligibility
source_date: '2026-11-09'
source_filename: asato-eligibility.yml
source_heading: Eligibility
source_page: https://www.asato.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Asato\naid: asato\nurl: https://www.asato.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or the age of majority in your jurisdiction to use our Services.\nrestricted_uses:\n- summary: Unlawful, disruptive, or harmful use\n  text: Use the Services for any unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or the age of majority in your jurisdiction to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/asato/eligibility/asato-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Asato's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- IT Asset Management
- Software-as-a-Service
- Cloud
---
