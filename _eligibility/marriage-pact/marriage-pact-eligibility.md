---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States.
  entity_types:
  - text: You may use the Service only if you can form a binding contract with Marriage Pact
    type: individual
  minimum_age:
    text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Use by under-13s prohibited
    text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.
  - summary: Use by previously removed users
    text: The Service is not available to any Users previously removed from the Service by Marriage Pact.
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
name: Marriage Pact
provenance_date: '2026-11-10'
provider_name: Marriage Pact
provider_slug: marriage-pact
slug: marriage-pact-eligibility
source_date: '2026-11-10'
source_filename: marriage-pact-eligibility.yml
source_heading: Eligibility
source_page: https://marriagepact.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Marriage Pact\naid: marriage-pact\nurl: https://marriagepact.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States.\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a binding contract with Marriage Pact\nrestricted_uses:\n- summary: Use by under-13s prohibited\n  text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this\
  \ Agreement.\n- summary: Use by previously removed users\n  text: The Service is not available to any Users previously removed from the Service by Marriage Pact.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/marriage-pact/eligibility/marriage-pact-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Marriage Pact's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Matchmaking
- Dating
- Consumer
- Compatibility
- Questionnaire
- Higher Education
---
