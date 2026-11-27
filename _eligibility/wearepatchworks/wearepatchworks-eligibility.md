---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any individual accepting the Agreement on behalf of Customer which is an organisation or other entity represents and warrants that they have the authority to bind Customer to the Agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted data types
    text: Customer shall not provide, upload, submit or otherwise make available to the Platform Services and Patchworks will not be liable for
  - summary: Illegal or fraudulent use
    text: (i) for fraudulent or illegal activities or purposes
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
name: Patchworks
provenance_date: '2026-11-10'
provider_name: Patchworks
provider_slug: wearepatchworks
slug: wearepatchworks-eligibility
source_date: '2026-11-10'
source_filename: wearepatchworks-eligibility.yml
source_heading: Eligibility
source_page: https://patchworks.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Patchworks\naid: wearepatchworks\nurl: https://patchworks.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Any individual accepting the Agreement on behalf of Customer which is an organisation or other entity represents\n    and warrants that they have the authority to bind Customer to the Agreement.\nrestricted_uses:\n- summary: Restricted data types\n  text: Customer shall not provide, upload, submit or otherwise make available to the Platform Services and Patchworks\n    will not be liable for\n- summary:\
  \ Illegal or fraudulent use\n  text: (i) for fraudulent or illegal activities or purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wearepatchworks/eligibility/wearepatchworks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Patchworks's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- E-Commerce
- ERP
- Automation
- Artificial Intelligence
---
