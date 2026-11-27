---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to, or use of, the System may be prohibited by law in certain jurisdictions. You are responsible for compliance with all applicable laws of the jurisdiction from which you are accessing the System.
  entity_types:
  - text: By using the System you confirm that you are 18 years of age or more
    type: individual
  minimum_age:
    text: By using the System you confirm that you are 18 years of age or more
    value: '18'
  restricted_uses:
  - summary: Not for medical treatment
    text: You agree and represent to Second Nature that you are not using Second Nature Service or System or participating in any of the activities offered by Second Nature for the purpose of seeking medical attention.
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
name: Second Nature
provenance_date: '2026-11-10'
provider_name: Second Nature
provider_slug: second-nature
slug: second-nature-eligibility
source_date: '2026-11-10'
source_filename: second-nature-eligibility.yml
source_heading: Eligibility
source_page: https://www.secondnature.io/us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Second Nature\naid: second-nature\nurl: https://www.secondnature.io/us/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to, or use of, the System may be prohibited by law in certain jurisdictions. You are responsible\n    for compliance with all applicable laws of the jurisdiction from which you are accessing the System.\nentity_types:\n- type: individual\n  text: By using the System you confirm that you are 18 years of age or more\nrestricted_uses:\n- summary: Not for medical treatment\n  text: You agree and represent to Second Nature that you are not using Second Nature\
  \ Service or System or participating\n    in any of the activities offered by Second Nature for the purpose of seeking medical attention.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the System you confirm that you are 18 years of age or more\n"
source_yaml_url: https://artifacts.apis.io/second-nature/eligibility/second-nature-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Second Nature's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Weight Loss
- Digital Health
- Healthcare
- Wellness
- Consumer
---
