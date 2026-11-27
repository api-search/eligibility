---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To be 18 or older
    type: individual
  - text: use the service only for apps you or your employer own
    type: business
  minimum_age:
    text: To be 18 or older
    value: '18'
  restricted_uses:
  - summary: Only apps you or your employer own
    text: use the service only for apps you or your employer own
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
name: asacondor-com
provenance_date: '2026-11-09'
provider_name: asacondor-com
provider_slug: asacondor-com
slug: asacondor-com-eligibility
source_date: '2026-11-09'
source_filename: asacondor-com-eligibility.yml
source_heading: Eligibility
source_page: https://asacondor.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: asacondor-com\naid: asacondor-com\nurl: https://asacondor.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To be 18 or older\n- type: business\n  text: use the service only for apps you or your employer own\nrestricted_uses:\n- summary: Only apps you or your employer own\n  text: use the service only for apps you or your employer own\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To be 18 or older\n"
source_yaml_url: https://artifacts.apis.io/asacondor-com/eligibility/asacondor-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from asacondor-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
