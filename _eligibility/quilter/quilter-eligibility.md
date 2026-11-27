---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: MATERIALS AND INFORMATION INTENDED FOR USERS OF THE SERVICE ARE NOT FOR USE BY CHILDREN UNDER 13 YEARS OF AGE
    value: '13'
  restricted_uses:
  - summary: No competing product
    text: (iv) access the Service for purposes of building or marketing a competitive product;
  - summary: Output not to compete with provider
    text: Use your Output to compete with Quilter;
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
name: Quilter
provenance_date: '2026-11-10'
provider_name: Quilter
provider_slug: quilter
slug: quilter-eligibility
source_date: '2026-11-10'
source_filename: quilter-eligibility.yml
source_heading: Eligibility
source_page: https://www.quilter.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quilter\naid: quilter\nurl: https://www.quilter.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you are agreeing to these Terms for that organization\nrestricted_uses:\n- summary: No competing product\n  text: (iv) access the Service for purposes of building or marketing a competitive product;\n- summary: Output not to compete with provider\n  text: Use your Output to compete with Quilter;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: MATERIALS AND INFORMATION INTENDED FOR USERS OF THE SERVICE ARE NOT FOR USE BY CHILDREN UNDER 13 YEARS OF\n    AGE\n"
source_yaml_url: https://artifacts.apis.io/quilter/eligibility/quilter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Quilter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- PCB Design
- EDA
- Electronics Design Automation
- Reinforcement Learning
- Hardware
- Automation
---
