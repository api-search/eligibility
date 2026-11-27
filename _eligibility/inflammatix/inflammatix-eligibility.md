---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a legal contract between you, either an individual visitor or user who is the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: THE SITE IS NOT AVAILABLE TO PERSONS UNDER THE AGE OF MAJORITY IN THEIR JURISDICTION
    value: age of majority in your jurisdiction
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
name: Inflammatix
provenance_date: '2026-11-09'
provider_name: Inflammatix
provider_slug: inflammatix
slug: inflammatix-eligibility
source_date: '2026-11-09'
source_filename: inflammatix-eligibility.yml
source_heading: Eligibility
source_page: https://inflammatix.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inflammatix\naid: inflammatix\nurl: https://inflammatix.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a legal contract between you, either an individual visitor or user who is the age of majority in your jurisdiction\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in your jurisdiction\n  text: THE SITE IS NOT AVAILABLE TO PERSONS UNDER THE AGE OF MAJORITY IN THEIR JURISDICTION\n"
source_yaml_url: https://artifacts.apis.io/inflammatix/eligibility/inflammatix-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Inflammatix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Diagnostics
- Medical Devices
- In Vitro Diagnostics
- Molecular Diagnostics
- Sepsis
- Machine Learning
- Life Sciences
- Point of Care
- Content
---
