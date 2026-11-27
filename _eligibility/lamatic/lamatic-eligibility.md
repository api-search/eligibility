---
api_specs:
- filename: lamatic-openapi-generated.yml
  format: yaml
  label: Lamatic API
  slug: lamatic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lamatic/openapi/_ae-authored/lamatic-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for users who are at least 18 years old.
    type: individual
  - text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated uses
    text: The Services are not tailored to comply with industry-specific regulations (such as the Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc .), so if your interactions would be subjected to such laws, you may not use the Services.
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
name: Lamatic
provenance_date: '2026-11-09'
provider_name: Lamatic
provider_slug: lamatic
slug: lamatic-eligibility
source_date: '2026-11-09'
source_filename: lamatic-eligibility.yml
source_heading: Eligibility
source_page: https://lamatic.ai/docs/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lamatic\naid: lamatic\nurl: https://lamatic.ai/docs/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended for users who are at least 18 years old.\n- type: business\n  text: These Legal Terms constitute a legally binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Industry-regulated uses\n  text: The Services are not tailored to comply with industry-specific regulations (such as the Health Insurance\n    Portability and Accountability\
  \ Act (HIPAA), Federal Information Security Management Act (FISMA), etc .), so\n    if your interactions would be subjected to such laws, you may not use the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Persons under the age of 18 are not permitted to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/lamatic/eligibility/lamatic-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lamatic's own page on 2026-11-09.
synthetic: false
tags:
- AI Middleware
- Generative AI
- Serverless deployment
- Integration
- Software-as-a-Service
- Enterprise
- Agency
---
