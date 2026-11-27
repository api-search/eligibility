---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Clinical interpretation
    text: Dozee requires trained medical professionals to interpret reports and act on alerts.
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
name: Dozee
provenance_date: '2026-11-09'
provider_name: Dozee
provider_slug: dozee
slug: dozee-eligibility
source_date: '2026-11-09'
source_filename: dozee-eligibility.yml
source_heading: Eligibility
source_page: https://www.dozeehealth.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dozee\naid: dozee\nurl: https://www.dozeehealth.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Clinical interpretation\n  text: Dozee requires trained medical professionals to interpret reports and act on alerts.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dozee/eligibility/dozee-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Dozee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Remote Monitoring
- Artificial Intelligence
- Ballistocardiography
---
