---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To be eligible to use the Platform, you represent, warrant and covenant that you: (A) Are eighteen (18) years of age or older'
    type: individual
  minimum_age:
    text: (A) Are eighteen (18) years of age or older - the Platform is not intended for use by anyone under the age of eighteen (18) years old;
    value: '18'
  restricted_uses:
  - summary: Competitive use
    text: (E) Are not using the Platform for reasons that are in competition with or adverse to Solace;
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
name: Solace
provenance_date: '2026-11-10'
provider_name: Solace
provider_slug: solace
slug: solace-eligibility
source_date: '2026-11-10'
source_filename: solace-eligibility.yml
source_heading: Eligibility
source_page: https://app.solace.health/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solace\naid: solace\nurl: https://app.solace.health/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To be eligible to use the Platform, you represent, warrant and covenant that you: (A) Are eighteen (18)\n    years of age or older'\nrestricted_uses:\n- summary: Competitive use\n  text: (E) Are not using the Platform for reasons that are in competition with or adverse to Solace;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (A) Are eighteen (18)\
  \ years of age or older - the Platform is not intended for use by anyone under the age\n    of eighteen (18) years old;\n"
source_yaml_url: https://artifacts.apis.io/solace/eligibility/solace-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Solace's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Patient Advocacy
- Care Navigation
- Medicare
- Consumer Health
---
