---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: binding you or the organization you represent ("you", "your", "Customer")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Competitive development
    text: Access or utilize the Services for developing a competitive product or service, or engage in any form of competitive analysis or benchmarking against the Services.
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
name: Mobagel
provenance_date: '2026-11-10'
provider_name: Mobagel
provider_slug: mobagel
slug: mobagel-eligibility
source_date: '2026-11-10'
source_filename: mobagel-eligibility.yml
source_heading: Eligibility
source_page: https://us.mobagel.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mobagel\naid: mobagel\nurl: https://us.mobagel.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: binding you or the organization you represent (\"you\", \"your\", \"Customer\")\nrestricted_uses:\n- summary: Competitive development\n  text: Access or utilize the Services for developing a competitive product or service, or engage in any form of\n    competitive analysis or benchmarking against the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/mobagel/eligibility/mobagel-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Mobagel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- AutoML
- Data Science
- Predictive Analytics
- Business Intelligence
- MLOps
---
