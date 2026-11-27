---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    served: []
    text: Customer represents and warrants that it is not (i) located, organized, or resident in a country or territory that is subject to a U.S. trade embargo (currently, Cuba, Iran, North Korea, Syria, Russia
  entity_types:
  - text: the customer identified on the Order Form, on behalf of itself and its Affiliates
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: use the Platform in whole or in part for any illegal purpose
  - summary: Processing Data for third parties
    text: processing Data using the Platform on behalf of third parties or any unaffiliated entities
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Halcyon
provenance_date: '2026-11-09'
provider_name: Halcyon
provider_slug: halcyon
slug: halcyon-eligibility
source_date: '2026-11-09'
source_filename: halcyon-eligibility.yml
source_heading: Eligibility
source_page: https://www.halcyon.ai/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halcyon\naid: halcyon\nurl: https://www.halcyon.ai/policies/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  text: Customer represents and warrants that it is not (i) located, organized, or resident in a country or territory\n    that is subject to a U.S. trade embargo (currently, Cuba, Iran, North Korea, Syria, Russia\nentity_types:\n- type: business\n  text: the customer identified on the Order Form, on behalf of itself and its Affiliates\nrestricted_uses:\n- summary: Illegal purposes\n  text: use the Platform in\
  \ whole or in part for any illegal purpose\n- summary: Processing Data for third parties\n  text: processing Data using the Platform on behalf of third parties or any unaffiliated entities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/halcyon/eligibility/halcyon-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Halcyon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Infrastructure
- Cybersecurity
- Ransomware
- Endpoint Security
- Threat Detection
- SIEM
---
