---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Business User Any User that does not qualify as a Consumer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use limits
    text: Users are solely responsible for making sure that their use of ChooseHelp and/or the Service violates no applicable law, regulations or third-party rights.
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
name: ChooseHelp.com
provenance_date: '2026-11-09'
provider_name: ChooseHelp.com
provider_slug: choosehelp-com
slug: choosehelp-com-eligibility
source_date: '2026-11-09'
source_filename: choosehelp-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.choosehelp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChooseHelp.com\naid: choosehelp-com\nurl: https://www.choosehelp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Business User Any User that does not qualify as a Consumer.\nrestricted_uses:\n- summary: Acceptable use limits\n  text: Users are solely responsible for making sure that their use of ChooseHelp and/or the Service violates no\n    applicable law, regulations or third-party rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/choosehelp-com/eligibility/choosehelp-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ChooseHelp.com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Addiction Treatment
- Mental Health
- Healthcare
- Directory
- Therapists
- MCP
---
