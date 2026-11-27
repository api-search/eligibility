---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Site.
    type: individual
  - text: if you access the Sites on behalf of a legal entity, to that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: Competitive use of the Sites
    text: use or apply the Sites in any manner directly or indirectly competitive with our business
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
name: Vianai Systems
provenance_date: '2026-11-10'
provider_name: Vianai Systems
provider_slug: vianai-systems
slug: vianai-systems-eligibility
source_date: '2026-11-10'
source_filename: vianai-systems-eligibility.yml
source_heading: Eligibility
source_page: https://www.vian.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vianai Systems\naid: vianai-systems\nurl: https://www.vian.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site.\n- type: business\n  text: if you access the Sites on behalf of a legal entity, to that entity\nrestricted_uses:\n- summary: Competitive use of the Sites\n  text: use or apply the Sites in any manner directly or indirectly competitive with our business\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/vianai-systems/eligibility/vianai-systems-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vianai Systems's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Artificial Intelligence
- Machine Learning
- MLOps
- Model Monitoring
- Analytics
- Generative AI
- Observability
- Conversational Analytics
---
