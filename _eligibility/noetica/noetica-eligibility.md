---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is intended for visitors located within the United States.
  entity_types:
  - text: you are an employee of the Organization
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service and an employee of the Organization.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: use the Service for any illegal purpose or in violation of any local, state, national, or international law;
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
name: Noetica
provenance_date: '2026-11-10'
provider_name: Noetica
provider_slug: noetica
slug: noetica-eligibility
source_date: '2026-11-10'
source_filename: noetica-eligibility.yml
source_heading: Eligibility
source_page: https://www.noetica.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noetica\naid: noetica\nurl: https://www.noetica.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is intended for visitors located within the United States.\nentity_types:\n- type: business\n  text: you are an employee of the Organization\nrestricted_uses:\n- summary: Illegal purposes\n  text: use the Service for any illegal purpose or in violation of any local, state, national, or international\n    law;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18\
  \ years old to use the Service and an employee of the Organization.\n"
source_yaml_url: https://artifacts.apis.io/noetica/eligibility/noetica-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Noetica's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal Tech
- Finance
- Deal Intelligence
- Market Data
- Artificial Intelligence
- Natural Language Processing
- Capital Markets
- Mergers and Acquisitions
---
