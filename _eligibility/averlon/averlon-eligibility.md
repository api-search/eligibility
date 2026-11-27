---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you or the entity you represent placing an Order for or accessing the Service (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer agrees not to use or export (directly or indirectly) the Software or related technology in violation of applicable export laws or regulations.
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
name: Averlon
provenance_date: '2026-11-09'
provider_name: Averlon
provider_slug: averlon
slug: averlon-eligibility
source_date: '2026-11-09'
source_filename: averlon-eligibility.yml
source_heading: Eligibility
source_page: https://www.averlon.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Averlon\naid: averlon\nurl: https://www.averlon.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you or the entity you represent placing an Order for or accessing the Service (“Customer”)\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer agrees not to use or export (directly or indirectly) the Software or related technology in violation\n    of applicable export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/averlon/eligibility/averlon-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Averlon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Artificial Intelligence
- Vulnerability Management
- Automation
---
