---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you personally (i.e., the individual who reads and agrees to be bound by these Terms)
    type: individual
  - text: if you access the Site on behalf of a legal entity, to that entity
    type: business
  minimum_age:
    text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Competitive use of the Site
    text: Use or apply the Site in any manner directly or indirectly competitive with any business of Tecton.
  - summary: Third-party applications
    text: Develop any third-party applications that interact with the Site or Content without our prior written consent.
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
name: Tecton (Databricks)
provenance_date: '2026-11-10'
provider_name: Tecton (Databricks)
provider_slug: tecton-databricks
slug: tecton-databricks-eligibility
source_date: '2026-11-10'
source_filename: tecton-databricks-eligibility.yml
source_heading: Eligibility
source_page: https://www.tecton.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tecton (Databricks)\naid: tecton-databricks\nurl: https://www.tecton.ai/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you personally (i.e., the individual who reads and agrees to be bound by these Terms)\n- type: business\n  text: if you access the Site on behalf of a legal entity, to that entity\nrestricted_uses:\n- summary: Competitive use of the Site\n  text: Use or apply the Site in any manner directly or indirectly competitive with any business of Tecton.\n- summary: Third-party applications\n  text: Develop any\
  \ third-party applications that interact with the Site or Content without our prior written consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU REPRESENT THAT YOU ARE AT LEAST 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/tecton-databricks/eligibility/tecton-databricks-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Tecton (Databricks)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Infrastructure
- Feature Store
- Feature Platform
- Machine Learning
- MLOps
- Real-Time
- Databricks
---
