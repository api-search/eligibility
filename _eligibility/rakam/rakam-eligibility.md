---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United State government.
  entity_types:
  - text: if you are using the Services on behalf of a company or other such legal entity, you represent that you have the authority to bind such entity to these Terms.
    type: business
  minimum_age:
    text: We do not knowingly collect data from or market to children under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Embargoed or blocked persons
    text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United State government.
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
name: rakam
provenance_date: '2026-11-10'
provider_name: rakam
provider_slug: rakam
slug: rakam-eligibility
source_date: '2026-11-10'
source_filename: rakam-eligibility.yml
source_heading: Eligibility
source_page: https://rakam.io/policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rakam\naid: rakam\nurl: https://rakam.io/policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United State government.\nentity_types:\n- type: business\n  text: if you are using the Services on behalf of a company or other such legal entity, you represent that you\n    have the authority to bind such entity to these Terms.\nrestricted_uses:\n- summary: Embargoed or blocked persons\n  text: You may not use the Services if\
  \ you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United State government.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not knowingly collect data from or market to children under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/rakam/eligibility/rakam-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from rakam's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Analytics
- Product Analytics
- Data Warehouse
- Business Intelligence
- Event Tracking
- dbt
- Embedded Analytics
- Semantic Layer
- Open Source
---
