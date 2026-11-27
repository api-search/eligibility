---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: To comply with these laws, Clairwave may block access from certain countries or regions, restrict particular features by location, and refuse or end access without notice.
  entity_types:
  - text: One person per account.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for safety-critical or regulatory decisions
    text: Do not rely on them for safety-of-life, navigation or regulatory compliance decisions.
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
name: Clairwave
provenance_date: '2026-11-09'
provider_name: Clairwave
provider_slug: clairwave-com
slug: clairwave-com-eligibility
source_date: '2026-11-09'
source_filename: clairwave-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.clairwave.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clairwave\naid: clairwave-com\nurl: https://www.clairwave.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: To comply with these laws, Clairwave may block access from certain countries or regions, restrict particular\n    features by location, and refuse or end access without notice.\nentity_types:\n- type: individual\n  text: One person per account.\nrestricted_uses:\n- summary: Not for safety-critical or regulatory decisions\n  text: Do not rely on them for safety-of-life, navigation or regulatory compliance decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clairwave-com/eligibility/clairwave-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Clairwave's own page on 2026-11-09.
synthetic: false
tags:
- Underwater Acoustics
- marine modeling
- environmental impact assessment
- Offshore Energy
- port and shipping
- AI Integration
---
