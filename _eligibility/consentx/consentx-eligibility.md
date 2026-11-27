---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for business and professional use and is not directed to consumers acting outside their trade or profession.
    type: business
  - text: To use the Service you must be at least the age of majority in your jurisdiction and capable of forming a binding contract.
    type: individual
  minimum_age:
    text: you must be at least the age of majority in your jurisdiction
    value: age of majority
  restricted_uses:
  - summary: Lawful purposes only
    text: use the Service only for lawful purposes and in compliance with Applicable Law and these terms
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
name: ConsentX
provenance_date: '2026-11-09'
provider_name: ConsentX
provider_slug: consentx
slug: consentx-eligibility
source_date: '2026-11-09'
source_filename: consentx-eligibility.yml
source_heading: Eligibility
source_page: https://www.consentx.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConsentX\naid: consentx\nurl: https://www.consentx.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is intended for business and professional use and is not directed to consumers acting outside\n    their trade or profession.\n- type: individual\n  text: To use the Service you must be at least the age of majority in your jurisdiction and capable of forming\n    a binding contract.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: use the Service only for lawful purposes and in compliance with Applicable\
  \ Law and these terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you must be at least the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/consentx/eligibility/consentx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ConsentX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CMP
- GDPR
- CCPA
- Privacy
- Consent Management
---
