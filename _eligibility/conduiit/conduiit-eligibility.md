---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Site, you represent that you are at least 18 years old or have legal parental or guardian consent.
    type: individual
  minimum_age:
    text: By using the Site, you represent that you are at least 18 years old or have legal parental or guardian consent.
    value: '18'
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
name: Conduiit
provenance_date: '2026-11-09'
provider_name: Conduiit
provider_slug: conduiit
slug: conduiit-eligibility
source_date: '2026-11-09'
source_filename: conduiit-eligibility.yml
source_heading: Eligibility
source_page: https://www.conduiit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conduiit\naid: conduiit\nurl: https://www.conduiit.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Site, you represent that you are at least 18 years old or have legal parental or guardian consent.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Site, you represent that you are at least 18 years old or have legal parental or guardian consent.\n"
source_yaml_url: https://artifacts.apis.io/conduiit/eligibility/conduiit-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Conduiit's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Film Production
- TVProduction
- TaxIncentives
- Expense Management
---
