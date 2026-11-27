---
claim_count: 2
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
  - summary: Abuse of limits or service
    text: Abuse (circumventing limits, resale of raw data, disrupting the service) may result in blocking.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: No account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: canienter-com
provenance_date: '2026-11-09'
provider_name: canienter-com
provider_slug: canienter-com
slug: canienter-com-eligibility
source_date: '2026-11-09'
source_filename: canienter-com-eligibility.yml
source_heading: Eligibility
source_page: https://canienter.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: canienter-com\naid: canienter-com\nurl: https://canienter.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Abuse of limits or service\n  text: Abuse (circumventing limits, resale of raw data, disrupting the service) may result in blocking.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: No account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/canienter-com/eligibility/canienter-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from canienter-com's own page on 2026-11-09.
synthetic: false
tags:
- Visa checks
- Entry requirements
- Travel
- Data Service
- Immigration
---
