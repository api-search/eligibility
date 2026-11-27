---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - CA
    - NZ
    - GB
    - US
    text: Countries Australia Canada New Zealand United Kingdom United States All countries
  entity_types:
  - text: Adding photos needs an account, which is just an email address and a code we send to it.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No advertising or network posting
    text: No advertising, and no posting on behalf of a charging network about its own or a rival's sites.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Adding photos needs an account, which is just an email address and a code we send to it. There is no password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chargealong.io
provenance_date: '2026-11-09'
provider_name: Chargealong.io
provider_slug: chargealong
slug: chargealong-eligibility
source_date: '2026-11-09'
source_filename: chargealong-eligibility.yml
source_heading: Eligibility
source_page: https://chargealong.io/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chargealong.io\naid: chargealong\nurl: https://chargealong.io/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  - CA\n  - NZ\n  - GB\n  - US\n  excluded: []\n  text: Countries Australia Canada New Zealand United Kingdom United States All countries\nentity_types:\n- type: individual\n  text: Adding photos needs an account, which is just an email address and a code we send to it.\nrestricted_uses:\n- summary: No advertising or network posting\n  text: No advertising, and no posting on behalf of a charging network about its own or a rival's sites.\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: Adding photos needs an account, which is just an email address and a code we send to it. There is no password.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chargealong/eligibility/chargealong-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Chargealong.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Electric Vehicles
- Charging
- Data
- Public APIs
- Australia
---
