---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization's or entity's behalf
    type: business
  minimum_age:
    text: We do not knowingly collect or solicit personally identifiable information from children under 13 years of age
    value: null
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
name: Eventual
provenance_date: '2026-11-09'
provider_name: Eventual
provider_slug: eventual
slug: eventual-eligibility
source_date: '2026-11-09'
source_filename: eventual-eligibility.yml
source_heading: Eligibility
source_page: https://www.eventual.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eventual\naid: eventual\nurl: https://www.eventual.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: If you're agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization's or entity's behalf\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: We do not knowingly collect or solicit personally identifiable information from children under 13 years\n    of age\n"
source_yaml_url: https://artifacts.apis.io/eventual/eligibility/eventual-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Eventual's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Data Engine
- Artificial Intelligence
- Multi-Modal
- Analytics
- Open Source
- Python
- Rust
- DataFrames
- Physical AI
- Distributed Computing
---
