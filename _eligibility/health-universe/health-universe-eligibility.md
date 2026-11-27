---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individually licensed clinician (for example, a sole practitioner identified by your own National Provider Identifier) accessing the Health Universe Platform on your own behalf
    type: individual
  - text: If you access the Health Universe Platform on behalf of an organization that has entered into a Master Services Agreement, Order Form, or Addendum with Health Universe, Inc.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: TEFCA non-treatment purposes
    text: for Payment, Health Care Operations, research, Individual Access Services, or any other non-Treatment Exchange Purpose
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Certain features, including nationwide record retrieval, are available only to licensed clinicians and other authorized personnel who have completed Health Universe’s identity verification and credentialing requirements
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Health Universe
provenance_date: '2026-11-09'
provider_name: Health Universe
provider_slug: health-universe
slug: health-universe-eligibility
source_date: '2026-11-09'
source_filename: health-universe-eligibility.yml
source_heading: Eligibility
source_page: https://www.healthuniverse.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Health Universe\naid: health-universe\nurl: https://www.healthuniverse.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individually licensed clinician (for example, a sole practitioner identified by your own National\n    Provider Identifier) accessing the Health Universe Platform on your own behalf\n- type: business\n  text: If you access the Health Universe Platform on behalf of an organization that has entered into a Master Services\n    Agreement, Order Form, or Addendum with Health Universe,\
  \ Inc.\nrestricted_uses:\n- summary: TEFCA non-treatment purposes\n  text: for Payment, Health Care Operations, research, Individual Access Services, or any other non-Treatment Exchange\n    Purpose\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Certain features, including nationwide record retrieval, are available only to licensed clinicians and other\n    authorized personnel who have completed Health Universe’s identity verification and credentialing requirements\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/health-universe/eligibility/health-universe-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Health Universe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- AI Agents
- Clinical
- Deployment
- FHIR
- A2A
- HIPAA
- Life Sciences
---
