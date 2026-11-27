---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: solely intended for and offered to users who are 13 years of age and older who reside in the United States
  entity_types:
  - text: if you are acting on behalf of a company or other entity, you have the authority to bind such company or entity
    type: business
  minimum_age:
    text: solely intended for and offered to users who are 13 years of age and older
    value: '13'
  restricted_uses:
  - summary: Violation of law or IP rights
    text: You may not access or use the Services in violation of applicable laws, including export controls and sanctions, or in violation of our or any third party’s intellectual property or other proprietary or legal rights.
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
name: Choose Energy
provenance_date: '2026-11-09'
provider_name: Choose Energy
provider_slug: choose-energy
slug: choose-energy-eligibility
source_date: '2026-11-09'
source_filename: choose-energy-eligibility.yml
source_heading: Eligibility
source_page: https://www.chooseenergy.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Choose Energy\naid: choose-energy\nurl: https://www.chooseenergy.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: solely intended for and offered to users who are 13 years of age and older who reside in the United States\nentity_types:\n- type: business\n  text: if you are acting on behalf of a company or other entity, you have the authority to bind such company or\n    entity\nrestricted_uses:\n- summary: Violation of law or IP rights\n  text: You may not access or use the Services in violation of applicable laws, including export controls and sanctions,\n\
  \    or in violation of our or any third party’s intellectual property or other proprietary or legal rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: solely intended for and offered to users who are 13 years of age and older\n"
source_yaml_url: https://artifacts.apis.io/choose-energy/eligibility/choose-energy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Choose Energy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Energy
- Electricity
- Natural Gas
- Marketplace
- Utilities
- Comparison
- Deregulated Energy
- Solar
---
