---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We may... You represent that you are not located in, and are not a national or resident of, any country subject to a comprehensive government embargo
  minimum_age:
    text: You must be at least 16 years old to create an account or use the Service.
    value: '16'
  restricted_uses:
  - summary: Not for unlawful or competing use
    text: use the Service in any way that is unlawful, fraudulent, or facilitates unlawful or fraudulent activity
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
name: Evertrain
provenance_date: '2026-11-09'
provider_name: Evertrain
provider_slug: evertrain-app
slug: evertrain-app-eligibility
source_date: '2026-11-09'
source_filename: evertrain-app-eligibility.yml
source_heading: Eligibility
source_page: https://evertrain.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Evertrain\naid: evertrain-app\nurl: https://evertrain.app/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We may... You represent that you are not located in, and are not a national or resident of, any country\n    subject to a comprehensive government embargo\nentity_types: []\nrestricted_uses:\n- summary: Not for unlawful or competing use\n  text: use the Service in any way that is unlawful, fraudulent, or facilitates unlawful or fraudulent activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You\
  \ must be at least 16 years old to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/evertrain-app/eligibility/evertrain-app-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Evertrain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Fitness
- Health
- Training
---
