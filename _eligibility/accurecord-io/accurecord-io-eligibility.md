---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is greater) to use the Services.
    type: individual
  - text: IF YOU ARE USING THE SERVICES ON BEHALF OF AN ORGANIZATION, YOU REPRESENT THAT YOU HAVE AUTHORITY TO BIND THAT ORGANIZATION
    type: business
  minimum_age:
    text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is greater)
    value: '18'
  restricted_uses:
  - summary: PHI only with executed BAA on eligible plans
    text: Individual ICD-10 Coding Pro accounts and Free or reference-only tiers do not support PHI or real patient charts.
  - summary: Not clinical decision support
    text: The Services are medical coding reference tools, not clinical decision support systems.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accurecord AI may require verification of such authority before granting organizational account access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Accurecord
provenance_date: '2026-11-09'
provider_name: Accurecord
provider_slug: accurecord-io
slug: accurecord-io-eligibility
source_date: '2026-11-09'
source_filename: accurecord-io-eligibility.yml
source_heading: Eligibility
source_page: https://accurecord.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Accurecord\naid: accurecord-io\nurl: https://accurecord.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is greater)\n    to use the Services.\n- type: business\n  text: IF YOU ARE USING THE SERVICES ON BEHALF OF AN ORGANIZATION, YOU REPRESENT THAT YOU HAVE AUTHORITY TO BIND\n    THAT ORGANIZATION\nrestricted_uses:\n- summary: PHI only with executed BAA on eligible plans\n  text: Individual ICD-10 Coding Pro accounts and Free or reference-only\
  \ tiers do not support PHI or real patient\n    charts.\n- summary: Not clinical decision support\n  text: The Services are medical coding reference tools, not clinical decision support systems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accurecord AI may require verification of such authority before granting organizational account access.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of majority in your jurisdiction, whichever is greater)\n"
source_yaml_url: https://artifacts.apis.io/accurecord-io/eligibility/accurecord-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Accurecord's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Coding
---
