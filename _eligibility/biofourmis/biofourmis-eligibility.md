---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use by consumers
    text: you agree not to use our site for any commercial or business purposes
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
name: Biofourmis
provenance_date: '2026-11-09'
provider_name: Biofourmis
provider_slug: biofourmis
slug: biofourmis-eligibility
source_date: '2026-11-09'
source_filename: biofourmis-eligibility.yml
source_heading: Eligibility
source_page: https://biofourmis.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Biofourmis\naid: biofourmis\nurl: https://biofourmis.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms'\nrestricted_uses:\n- summary: No commercial use by consumers\n  text: you agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/biofourmis/eligibility/biofourmis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Biofourmis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Digital Health
- Remote Patient Monitoring
- Hospital at Home
- Care Delivery
- Life Sciences
- Health Tech
- Wearables
---
