---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you access or use the Service from outside of the United States, you do so at your own risk.
  entity_types:
  - text: The Service is for your personal use.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    value: '18'
  restricted_uses:
  - summary: Competitors barred without written permission
    text: No employee, independent contractor, agent, or affiliate of any competing company is permitted to view, access, or use any portion of the Service without express written permission from Dawn.
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
name: Dawn
provenance_date: '2026-11-09'
provider_name: Dawn
provider_slug: dawn
slug: dawn-eligibility
source_date: '2026-11-09'
source_filename: dawn-eligibility.yml
source_heading: Eligibility
source_page: https://www.dawn.health/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dawn\naid: dawn\nurl: https://www.dawn.health/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you access or use the Service from outside of the United States, you do so at your own risk.\nentity_types:\n- type: individual\n  text: The Service is for your personal use.\nrestricted_uses:\n- summary: Competitors barred without written permission\n  text: No employee, independent contractor, agent, or affiliate of any competing company is permitted to view,\n    access, or use any portion of the Service without express written permission from Dawn.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/dawn/eligibility/dawn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dawn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Health
- Healthcare
- Sleep
- Insomnia
- CBT-I
- Telehealth
- Mental Health
- Consumer Health
---
