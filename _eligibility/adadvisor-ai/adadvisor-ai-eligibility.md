---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old and capable of entering into a legally binding agreement to use our Services.
    value: '18'
  restricted_uses:
  - summary: Acceptable use restrictions
    text: Violate any applicable law, regulation, or third-party rights
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
name: AdAdvisor
provenance_date: '2026-11-09'
provider_name: AdAdvisor
provider_slug: adadvisor-ai
slug: adadvisor-ai-eligibility
source_date: '2026-11-09'
source_filename: adadvisor-ai-eligibility.yml
source_heading: Eligibility
source_page: https://adadvisor.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AdAdvisor\naid: adadvisor-ai\nurl: https://adadvisor.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: Violate any applicable law, regulation, or third-party rights\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and\
  \ capable of entering into a legally binding agreement to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/adadvisor-ai/eligibility/adadvisor-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AdAdvisor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Advertising
- Media Buying
- Marketing Automation
- Software-as-a-Service
---
