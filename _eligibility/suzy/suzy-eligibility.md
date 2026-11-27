---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: When using the Services on behalf of an organization, you agree to these terms on behalf of that organization and you represent that you have the authority to do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable Use Policy applies
    text: All use of the Services shall be in accordance at all times with the Suzy Acceptable Use Policy
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
name: Suzy
provenance_date: '2026-11-10'
provider_name: Suzy
provider_slug: suzy
slug: suzy-eligibility
source_date: '2026-11-10'
source_filename: suzy-eligibility.yml
source_heading: Eligibility
source_page: https://www.suzy.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Suzy\naid: suzy\nurl: https://www.suzy.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: When using the Services on behalf of an organization, you agree to these terms on behalf of that organization\n    and you represent that you have the authority to do so.\nrestricted_uses:\n- summary: Acceptable Use Policy applies\n  text: All use of the Services shall be in accordance at all times with the Suzy Acceptable Use Policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/suzy/eligibility/suzy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Suzy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Consumer Insights
- Market Research
- Surveys
- Audiences
- Artificial Intelligence
---
