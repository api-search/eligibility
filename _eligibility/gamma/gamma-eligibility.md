---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services are controlled and offered by Gamma from its facilities in the United States of America. Gamma makes no representations that Services are appropriate or available for use in other locations.
  entity_types:
  - text: you are of legal age to form a binding contract
    type: individual
  - text: authority to enter into these terms personally or on behalf of the entity you have named as the user
    type: business
  minimum_age:
    text: You represent that you are (i) at least sixteen (16) years old
    value: '16'
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
name: Gamma
provenance_date: '2026-11-09'
provider_name: Gamma
provider_slug: gamma
slug: gamma-eligibility
source_date: '2026-11-09'
source_filename: gamma-eligibility.yml
source_heading: Eligibility
source_page: https://gamma.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gamma\naid: gamma\nurl: https://gamma.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Services are controlled and offered by Gamma from its facilities in the United States of America. Gamma\n    makes no representations that Services are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you are of legal age to form a binding contract\n- type: business\n  text: authority to enter into these terms personally or on behalf of the entity you have named as the user\nrestricted_uses: []\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You represent that you are (i) at least sixteen (16) years old\n"
source_yaml_url: https://artifacts.apis.io/gamma/eligibility/gamma-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Gamma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Productivity
- Presentations
- Documents
- Websites
- Artificial Intelligence
- Generative AI
- Content Generation
- Design
---
