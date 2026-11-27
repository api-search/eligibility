---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By creating an account or using Tsenta, you confirm that you are at least 18 years old and have the legal capacity to enter into these Terms.
    type: individual
  - text: If you are using Tsenta on behalf of an organization, you represent that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: you confirm that you are at least 18 years old
    value: '18'
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
name: Tsenta
provenance_date: '2026-11-10'
provider_name: Tsenta
provider_slug: tsenta
slug: tsenta-eligibility
source_date: '2026-11-10'
source_filename: tsenta-eligibility.yml
source_heading: Eligibility
source_page: https://tsenta.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tsenta\naid: tsenta\nurl: https://tsenta.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By creating an account or using Tsenta, you confirm that you are at least 18 years old and have the legal\n    capacity to enter into these Terms.\n- type: business\n  text: If you are using Tsenta on behalf of an organization, you represent that you have the authority to bind\n    that organization to these Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: you confirm that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/tsenta/eligibility/tsenta-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Tsenta's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Job
- Recruiting
- Job Search
- AI Agents
- Automation
- Applicant Tracking
- Careers
- MCP
- Y Combinator
---
