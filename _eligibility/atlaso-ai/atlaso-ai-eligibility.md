---
api_specs:
- filename: atlaso-ai-openapi-generated.yml
  format: yaml
  label: Atlaso Labs Inc. API
  slug: atlaso-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlaso-ai/openapi/_ae-authored/atlaso-ai-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you can form a binding contract with us and are not barred from doing so under applicable law.
    type: individual
  - text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you have authority to bind that entity, in which case "You" refers to that entity.
    type: business
  minimum_age:
    text: You must be at least 13 years old to create an Account or use the Service, and at least 18 years old if you are in India.
    value: '13'
  restricted_uses:
  - summary: No regulated data storage
    text: The Service is not designed for, and you must not use it to store, regulated data such as protected health information (PHI) or payment-card data unless separately agreed with us in writing.
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
name: Atlaso Labs Inc.
provenance_date: '2026-11-09'
provider_name: Atlaso Labs Inc.
provider_slug: atlaso-ai
slug: atlaso-ai-eligibility
source_date: '2026-11-09'
source_filename: atlaso-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.atlaso.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlaso Labs Inc.\naid: atlaso-ai\nurl: https://www.atlaso.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you can form a binding contract with us and are not barred from doing so\n    under applicable law.\n- type: business\n  text: If you are entering into these Terms on behalf of a company or other legal entity, you represent that you\n    have authority to bind that entity, in which case \"You\" refers to that entity.\nrestricted_uses:\n- summary: No regulated data storage\n  text: The Service\
  \ is not designed for, and you must not use it to store, regulated data such as protected health\n    information (PHI) or payment-card data unless separately agreed with us in writing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to create an Account or use the Service, and at least 18 years old if\n    you are in India.\n"
source_yaml_url: https://artifacts.apis.io/atlaso-ai/eligibility/atlaso-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Atlaso Labs Inc.'s own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Integration
- Platform
- Tools
---
