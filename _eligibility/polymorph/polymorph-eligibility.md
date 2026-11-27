---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization, you represent that you are authorized to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Malicious code or infringement
    text: Use the Services to store or transmit malicious code or to infringe the rights of others.
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
name: Polymorph
provenance_date: '2026-11-10'
provider_name: Polymorph
provider_slug: polymorph
slug: polymorph-eligibility
source_date: '2026-11-10'
source_filename: polymorph-eligibility.yml
source_heading: Eligibility
source_page: https://usepolymorph.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Polymorph\naid: polymorph\nurl: https://usepolymorph.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you are authorized to bind\n    that organization.\nrestricted_uses:\n- summary: Malicious code or infringement\n  text: Use the Services to store or transmit malicious code or to infringe the rights of others.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be\
  \ at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/polymorph/eligibility/polymorph-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Polymorph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Personalization
- Experimentation
- Consumer Internet
- Artificial Intelligence
- Machine Learning
- Growth
- Y Combinator
---
