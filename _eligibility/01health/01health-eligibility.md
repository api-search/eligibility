---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual practitioner, if that person is operating in business as an individual
    type: individual
  - text: the company, partnership, practice or other entity which employs or engages the individual practitioner or on whose behalf the individual practitioner acts
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: not for consumers
    text: Our Service is not for use by consumers.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you will be required to provide certain information to us, including information concerning professional status, registration and experience.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 01health
provenance_date: '2026-11-09'
provider_name: 01health
provider_slug: 01health
slug: 01health-eligibility
source_date: '2026-11-09'
source_filename: 01health-eligibility.yml
source_heading: Eligibility
source_page: https://01health.ai/us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 01health\naid: 01health\nurl: https://01health.ai/us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual practitioner, if that person is operating in business as an individual\n- type: business\n  text: the company, partnership, practice or other entity which employs or engages the individual practitioner\n    or on whose behalf the individual practitioner acts\nrestricted_uses:\n- summary: not for consumers\n  text: Our Service is not for use by consumers.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: you will be required to provide certain information to us, including information concerning professional\n    status, registration and experience.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/01health/eligibility/01health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from 01health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Dental
- Clinical
- Digital Health
- Specialist Care
- Sleep Medicine
- Orthodontics
---
