---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer may not access or use the Services if located in any Prohibited Jurisdiction under U.S. or other applicable laws.
  entity_types:
  - text: the customer set forth on the Order Form (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: Customer will not access or use the Services if Customer or any Authorized Users are located in any jurisdiction in which the provision of the Services, software, or other components is prohibited under U.S. or other applicable laws or regulations
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
name: Plenful
provenance_date: '2026-11-10'
provider_name: Plenful
provider_slug: plenful
slug: plenful-eligibility
source_date: '2026-11-10'
source_filename: plenful-eligibility.yml
source_heading: Eligibility
source_page: https://www.plenful.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plenful\naid: plenful\nurl: https://www.plenful.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer may not access or use the Services if located in any Prohibited Jurisdiction under U.S. or other\n    applicable laws.\nentity_types:\n- type: business\n  text: the customer set forth on the Order Form (“Customer”)\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: Customer will not access or use the Services if Customer or any Authorized Users are located in any jurisdiction\n    in which the provision of the Services, software, or other components\
  \ is prohibited under U.S. or other applicable\n    laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/plenful/eligibility/plenful-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Plenful's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy
- Artificial Intelligence
- Workflow Automation
- Machine Learning
- 340B
- Prior Authorization
---
