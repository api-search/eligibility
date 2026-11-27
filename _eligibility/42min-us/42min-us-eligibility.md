---
api_specs:
- filename: 42min-us-api-openapi.yml
  format: yaml
  label: 42min API API
  slug: 42min-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/42min-us/openapi/_original/42min-us-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: Located in or a national of any country or region subject to comprehensive U.S. sanctions (currently including Cuba, Iran, North Korea, Syria, the Crimea region of Ukraine
  entity_types:
  - text: You are at least 16 years old , or the age of digital consent in your jurisdiction (if higher)
    type: individual
  - text: If you create an account on behalf of an organization, you represent that you have authority to bind that organization, and "you" refers to that organization.
    type: business
  minimum_age:
    text: Users 16 years or older (or the age of digital consent in your jurisdiction, if higher).
    value: '16'
  restricted_uses:
  - summary: No HIPAA or PHI workflows
    text: Use the Service for HIPAA-regulated workflows or electronic protected health information (PHI), since we are not a HIPAA Business Associate and do not sign Business Associate Agreements
  - summary: No special category personal data without approval
    text: Collect special category personal data (health, biometric, racial or ethnic origin, political opinions, religion, sex life, sexual orientation, genetic data, trade union membership, criminal records) through the Service without our prior written approval
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
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 42min
provenance_date: '2026-11-09'
provider_name: 42min
provider_slug: 42min-us
slug: 42min-us-eligibility
source_date: '2026-11-09'
source_filename: 42min-us-eligibility.yml
source_heading: Eligibility
source_page: https://42min.us/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 42min\naid: 42min-us\nurl: https://42min.us/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: Located in or a national of any country or region subject to comprehensive U.S. sanctions (currently including\n    Cuba, Iran, North Korea, Syria, the Crimea region of Ukraine\nentity_types:\n- type: individual\n  text: You are at least 16 years old , or the age of digital consent in your jurisdiction (if higher)\n- type: business\n  text: If you create an account on behalf of an organization, you represent that you have authority to bind that\n  \
  \  organization, and \"you\" refers to that organization.\nrestricted_uses:\n- summary: No HIPAA or PHI workflows\n  text: Use the Service for HIPAA-regulated workflows or electronic protected health information (PHI), since we\n    are not a HIPAA Business Associate and do not sign Business Associate Agreements\n- summary: No special category personal data without approval\n  text: Collect special category personal data (health, biometric, racial or ethnic origin, political opinions,\n    religion, sex life, sexual orientation, genetic data, trade union membership, criminal records) through the\n    Service without our prior written approval\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Users 16 years or older (or the age of digital consent in your jurisdiction, if higher).\n"
source_yaml_url: https://artifacts.apis.io/42min-us/eligibility/42min-us-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from 42min's own page on 2026-11-09.
synthetic: false
tags:
- Scheduling
- Free
- Webhook
- Automation
---
