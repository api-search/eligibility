---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We serve customers globally.
  entity_types:
  - text: You must be at least 13 years old to use the Services (additional parental/guardian consent may be required where applicable).
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Services
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: Upload unlawful, hateful, harassing, or pornographic material, or content inappropriate for those under 13.
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
name: All3D
provenance_date: '2026-11-09'
provider_name: All3D
provider_slug: all3d
slug: all3d-eligibility
source_date: '2026-11-09'
source_filename: all3d-eligibility.yml
source_heading: Eligibility
source_page: https://all3d.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: All3D\naid: all3d\nurl: https://all3d.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We serve customers globally.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Services (additional parental/guardian consent may be required\n    where applicable).\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: Upload unlawful, hateful, harassing, or pornographic material, or content inappropriate for those under\n    13.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '13'\n  text: You must be at least 13 years old to use the Services\n"
source_yaml_url: https://artifacts.apis.io/all3d/eligibility/all3d-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from All3D's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- 3D
- E-Commerce
- Product Imagery
- Visualization
- Generative AI
- Augmented Reality
- Retail
- Video Generation
---
