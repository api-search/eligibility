---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Individual or Company that the Individual is representing, intending to use or using our Services, whether in individual capacity
    type: individual
  - text: representing a registered legal entity
    type: business
  minimum_age:
    text: You will not register for an account if you are under 16 years of age
    value: '16'
  restricted_uses:
  - summary: Unlawful, misleading, malicious or discriminatory promotion
    text: You will not use the Platform for promoting anything that is considered to be unlawful, misleading, malicious or discriminatory
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Digitap authenticates the user through OTP mechanism and also creates a user account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Digitap.AI
provenance_date: '2026-11-09'
provider_name: Digitap.AI
provider_slug: digitap
slug: digitap-eligibility
source_date: '2026-11-09'
source_filename: digitap-eligibility.yml
source_heading: Eligibility
source_page: https://www.digitap.ai/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Digitap.AI\naid: digitap\nurl: https://www.digitap.ai/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Individual or Company that the Individual is representing, intending to use or using our Services, whether\n    in individual capacity\n- type: business\n  text: representing a registered legal entity\nrestricted_uses:\n- summary: Unlawful, misleading, malicious or discriminatory promotion\n  text: You will not use the Platform for promoting anything that is considered to be unlawful, misleading, malicious\n \
  \   or discriminatory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Digitap authenticates the user through OTP mechanism and also creates a user account.\nminimum_age:\n  value: '16'\n  text: You will not register for an account if you are under 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/digitap/eligibility/digitap-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Digitap.AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Banking
- Fintech
- Artificial Intelligence
- Software-as-a-Service
---
