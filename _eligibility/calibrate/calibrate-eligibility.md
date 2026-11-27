---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Services is limited exclusively to users located in states within the United States where the Services are available.
  entity_types:
  - text: You represent and warrant that you are an individual of legal age in your state of residence to enter into a binding contract.
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age in your state of residence to enter into a binding contract.
    value: null
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: You may only use the Services for your own internal, personal, non-commercial use, and not on behalf of or for the benefit of any third party
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
name: Calibrate
provenance_date: '2026-11-09'
provider_name: Calibrate
provider_slug: calibrate
slug: calibrate-eligibility
source_date: '2026-11-09'
source_filename: calibrate-eligibility.yml
source_heading: Eligibility
source_page: https://www.joincalibrate.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Calibrate\naid: calibrate\nurl: https://www.joincalibrate.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Services is limited exclusively to users located in states within the United States\n    where the Services are available.\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age in your state of residence to enter into\n    a binding contract.\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: You may only use the Services for your own internal, personal,\
  \ non-commercial use, and not on behalf of\n    or for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are an individual of legal age in your state of residence to enter into\n    a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/calibrate/eligibility/calibrate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Calibrate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Weight Loss
- Metabolic Health
- GLP-1
- Digital Health
---
