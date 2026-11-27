---
api_specs:
- filename: xing-openapi-generated.yml
  format: yaml
  label: XING API
  slug: xing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xing/openapi/_ae-authored/xing-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: XING SE & Co. KG provides selected developers and companies (hereafter referred to as Consumer) with the XING API
    type: developer
  - text: XING SE & Co. KG provides selected developers and companies (hereafter referred to as Consumer) with the XING API
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No collection of XING credentials
    text: Applications must not contain any features that query, collect or reproduce XING user names or passwords.
  - summary: No direct messaging through XING
    text: XING’s messaging features must not be used by Applications to directly communicate with users.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The Consumer has no right to register for the XING API and XING SE & Co. KG can decide at its own discretion who is permitted to use the XING API.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: XING
provenance_date: '2026-11-10'
provider_name: XING
provider_slug: xing
slug: xing-eligibility
source_date: '2026-11-10'
source_filename: xing-eligibility.yml
source_heading: Eligibility
source_page: https://dev.xing.com/api/terms_and_conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: XING\naid: xing\nurl: https://dev.xing.com/api/terms_and_conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: XING SE & Co. KG provides selected developers and companies (hereafter referred to as Consumer) with the\n    XING API\n- type: business\n  text: XING SE & Co. KG provides selected developers and companies (hereafter referred to as Consumer) with the\n    XING API\nrestricted_uses:\n- summary: No collection of XING credentials\n  text: Applications must not contain any features that query, collect or\
  \ reproduce XING user names or passwords.\n- summary: No direct messaging through XING\n  text: XING’s messaging features must not be used by Applications to directly communicate with users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The Consumer has no right to register for the XING API and XING SE & Co. KG can decide at its own discretion\n    who is permitted to use the XING API.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xing/eligibility/xing-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from XING's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Networking
- Job
- Recruiters
- Europe
---
