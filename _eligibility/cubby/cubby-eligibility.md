---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing or using the API on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Infringing or unlawful use
    text: use the API in any manner or for any purpose that infringes, misappropriates, or otherwise violates any intellectual property right or other right of any person, or that violates any applicable law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must obtain an API Key directly from Cubby.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cubby
provenance_date: '2026-11-09'
provider_name: Cubby
provider_slug: cubby
slug: cubby-eligibility
source_date: '2026-11-09'
source_filename: cubby-eligibility.yml
source_heading: Eligibility
source_page: https://www.cubbystorage.com/api-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cubby\naid: cubby\nurl: https://www.cubbystorage.com/api-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing or using the API on behalf of a company or other legal entity, you represent and warrant\n    that you have the authority to bind that entity\nrestricted_uses:\n- summary: Infringing or unlawful use\n  text: use the API in any manner or for any purpose that infringes, misappropriates, or otherwise violates any\n    intellectual property right or other right of any person, or that violates any\
  \ applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must obtain an API Key directly from Cubby.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cubby/eligibility/cubby-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Cubby's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Self Storage
- Property Management
- Facility Management
- Real Estate
- Payments
- Software-as-a-Service
- Artificial Intelligence
- Revenue Management
- E-Commerce
---
