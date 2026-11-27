---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: within the United States
  entity_types:
  - text: The license granted to Customer hereunder is solely for Customer's internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use in violation of law or HIPAA
    text: Use the Service in violation of any law, including without limitation, HIPAA and applicable privacy laws
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
name: Camber
provenance_date: '2026-11-09'
provider_name: Camber
provider_slug: camber
slug: camber-eligibility
source_date: '2026-11-09'
source_filename: camber-eligibility.yml
source_heading: Eligibility
source_page: https://www.camber.health/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Camber\naid: camber\nurl: https://www.camber.health/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: within the United States\nentity_types:\n- type: business\n  text: The license granted to Customer hereunder is solely for Customer's internal business purposes\nrestricted_uses:\n- summary: Use in violation of law or HIPAA\n  text: Use the Service in violation of any law, including without limitation, HIPAA and applicable privacy laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/camber/eligibility/camber-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Camber's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Revenue Cycle Management
- Medical Billing
- Claims
- Behavioral Health
- Health Tech
---
