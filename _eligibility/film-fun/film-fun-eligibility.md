---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under the age of 18 ("Minor"), your use of Services shall be permitted with the consent of your parent or legal guardian and their acceptance of Terms set forth herein.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age or the minimum age required in your jurisdiction to consent to use the Services
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: To only access or use the Services for lawful purposes
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
name: film-fun
provenance_date: '2026-11-09'
provider_name: film-fun
provider_slug: film-fun
slug: film-fun-eligibility
source_date: '2026-11-09'
source_filename: film-fun-eligibility.yml
source_heading: Eligibility
source_page: https://www.film.fun/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: film-fun\naid: film-fun\nurl: https://www.film.fun/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under the age of 18 (\"Minor\"), your use of Services shall be permitted with the consent of your\n    parent or legal guardian and their acceptance of Terms set forth herein.\nrestricted_uses:\n- summary: Lawful use only\n  text: To only access or use the Services for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at\
  \ least 18 years of age or the minimum age required in your jurisdiction to consent to use\n    the Services\n"
source_yaml_url: https://artifacts.apis.io/film-fun/eligibility/film-fun-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from film-fun's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Editing
- Filmmaking
- Platform
---
