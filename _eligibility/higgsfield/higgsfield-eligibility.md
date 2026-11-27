---
api_specs:
- filename: higgsfield-kling-video-api-openapi.yml
  format: yaml
  label: Higgsfield Kling Video API
  slug: higgsfield-kling-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/higgsfield/openapi/higgsfield-kling-video-api-openapi.yml
- filename: higgsfield-minimax-api-openapi.yml
  format: yaml
  label: Higgsfield Minimax API
  slug: higgsfield-minimax-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/higgsfield/openapi/higgsfield-minimax-api-openapi.yml
- filename: higgsfield-requests-api-openapi.yml
  format: yaml
  label: Higgsfield Requests API
  slug: higgsfield-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/higgsfield/openapi/higgsfield-requests-api-openapi.yml
- filename: higgsfield-soul-api-openapi.yml
  format: yaml
  label: Higgsfield Soul API
  slug: higgsfield-soul-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/higgsfield/openapi/higgsfield-soul-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of legal majority in your jurisdiction if higher, to create an Account or use the Service.
    type: individual
  - text: Enterprise, business, or organizational use of the Service may be governed by a separate written agreement between you and Company
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of legal majority in your jurisdiction if higher, to create an Account or use the Service.
    value: '18'
  restricted_uses:
  - summary: Protected health or payment card data via Developer Access
    text: use Developer Access to process Protected Health Information
  - summary: Biometric identification
    text: you may not use the Service to uniquely identify, verify, or authenticate any individual
  - summary: Inferring sensitive attributes
    text: use the Service to infer, predict, or classify (including through biometric categorization) the sensitive or protected-class attributes of any identifiable individual
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
name: Higgsfield
provenance_date: '2026-11-09'
provider_name: Higgsfield
provider_slug: higgsfield
slug: higgsfield-eligibility
source_date: '2026-11-09'
source_filename: higgsfield-eligibility.yml
source_heading: Eligibility
source_page: https://higgsfield.ai/terms-of-use-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Higgsfield\naid: higgsfield\nurl: https://higgsfield.ai/terms-of-use-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction if higher, to create\n    an Account or use the Service.\n- type: business\n  text: Enterprise, business, or organizational use of the Service may be governed by a separate written agreement\n    between you and Company\nrestricted_uses:\n- summary: Protected health or payment card data via Developer Access\n\
  \  text: use Developer Access to process Protected Health Information\n- summary: Biometric identification\n  text: you may not use the Service to uniquely identify, verify, or authenticate any individual\n- summary: Inferring sensitive attributes\n  text: use the Service to infer, predict, or classify (including through biometric categorization) the sensitive\n    or protected-class attributes of any identifiable individual\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of legal majority in your jurisdiction if higher, to create\n    an Account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/higgsfield/eligibility/higgsfield-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Higgsfield's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Video Generation
- Image Generation
- Machine Learning
- Media
- Content Creation
- Developer API
---
