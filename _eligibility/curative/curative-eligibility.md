---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: either an individual visitor or user who is the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: THE SITE IS NOT AVAILABLE TO PERSONS UNDER THE AGE OF MAJORITY IN THEIR JURISDICTION
    value: age of majority
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: Any suspected fraudulent, abusive, or illegal activity may be referred to appropriate law enforcement authorities.
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
name: Curative
provenance_date: '2026-11-09'
provider_name: Curative
provider_slug: curative
slug: curative-eligibility
source_date: '2026-11-09'
source_filename: curative-eligibility.yml
source_heading: Eligibility
source_page: https://curative.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curative\naid: curative\nurl: https://curative.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: either an individual visitor or user who is the age of majority in your jurisdiction\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: Any suspected fraudulent, abusive, or illegal activity may be referred to appropriate law enforcement authorities.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: THE SITE IS NOT AVAILABLE TO PERSONS\
  \ UNDER THE AGE OF MAJORITY IN THEIR JURISDICTION\n"
source_yaml_url: https://artifacts.apis.io/curative/eligibility/curative-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Curative's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Insurance
- Healthcare
- Health Plans
- Employer Benefits
- Preventative Care
- Insurtech
- HIPAA
---
