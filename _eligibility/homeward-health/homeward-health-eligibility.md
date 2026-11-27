---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Homeward websites are available only to individuals who can enter legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unauthorized or illegal purpose
    text: you may not (i) use Homeward websites for any unauthorized or illegal purpose or activity
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
name: Homeward Health
provenance_date: '2026-11-09'
provider_name: Homeward Health
provider_slug: homeward-health
slug: homeward-health-eligibility
source_date: '2026-11-09'
source_filename: homeward-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.homewardhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Homeward Health\naid: homeward-health\nurl: https://www.homewardhealth.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Homeward websites are available only to individuals who can enter legally binding contracts under applicable\n    law.\nrestricted_uses:\n- summary: Unauthorized or illegal purpose\n  text: you may not (i) use Homeward websites for any unauthorized or illegal purpose or activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/homeward-health/eligibility/homeward-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Homeward Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Rural Health
- Value-Based Care
- Medicare Advantage
- Telehealth
- Remote Patient Monitoring
- Primary Care
---
