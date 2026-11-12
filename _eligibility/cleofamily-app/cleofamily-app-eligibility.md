---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Cleo · Beta · US only
  entity_types:
  - text: The account is yours as a parent or legal guardian, not your child's.
    type: individual
  minimum_age:
    text: Children should not independently register for or operate a Cleo account.
    value: null
  restricted_uses:
  - summary: Personal use only
    text: Cleo is for personal use only.
  - summary: No commercial or unlawful purpose
    text: Use the apps for any commercial or unlawful purpose.
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
name: Cleo
provenance_date: '2026-11-09'
provider_name: Cleo
provider_slug: cleofamily-app
slug: cleofamily-app-eligibility
source_date: '2026-11-09'
source_filename: cleofamily-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.cleofamily.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleo\naid: cleofamily-app\nurl: https://www.cleofamily.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Cleo · Beta · US only\nentity_types:\n- type: individual\n  text: The account is yours as a parent or legal guardian, not your child's.\nrestricted_uses:\n- summary: Personal use only\n  text: Cleo is for personal use only.\n- summary: No commercial or unlawful purpose\n  text: Use the apps for any commercial or unlawful purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: Children should\
  \ not independently register for or operate a Cleo account.\n"
source_yaml_url: https://artifacts.apis.io/cleofamily-app/eligibility/cleofamily-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cleo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Family
- Parenting
- Baby Tracking
- Meal Planning
- MCP
- AI Assistants
- Productivity
---
