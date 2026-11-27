---
api_specs:
- filename: createprints-ai-account-api-openapi.yml
  format: yaml
  label: Create Prints Account API
  slug: createprints-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-account-api-openapi.yml
- filename: createprints-ai-artwork-api-openapi.yml
  format: yaml
  label: Create Prints Artwork API
  slug: createprints-ai-artwork-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-artwork-api-openapi.yml
- filename: createprints-ai-checkout-api-openapi.yml
  format: yaml
  label: Create Prints Checkout API
  slug: createprints-ai-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-checkout-api-openapi.yml
- filename: createprints-ai-orders-api-openapi.yml
  format: yaml
  label: Create Prints Orders API
  slug: createprints-ai-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-orders-api-openapi.yml
- filename: createprints-ai-product-discovery-api-openapi.yml
  format: yaml
  label: Create Prints Product discovery API
  slug: createprints-ai-product-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createprints-ai/openapi/createprints-ai-product-discovery-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - US
    text: Fulfilled locally for Great Britain and US delivery
  entity_types:
  - text: You must be at least 13 years old to create an account or use the Service.
    type: individual
  - text: If you use the Service wholly for business purposes, then to the extent permitted by law we exclude liability for indirect or consequential loss
    type: business
  minimum_age:
    text: You must be at least 13 years old to create an account or use the Service.
    value: '13'
  restricted_uses:
  - summary: Sexual content involving minors
    text: create sexual content involving minors or non-consensual intimate imagery
  - summary: Impersonation of real persons
    text: impersonate or misleadingly depict a real person
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may ask you to verify account or order information where reasonably necessary for security or fraud prevention.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Create Prints
provenance_date: '2026-11-09'
provider_name: Create Prints
provider_slug: createprints-ai
slug: createprints-ai-eligibility
source_date: '2026-11-09'
source_filename: createprints-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.createprints.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Create Prints\naid: createprints-ai\nurl: https://www.createprints.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - US\n  excluded: []\n  text: Fulfilled locally for Great Britain and US delivery\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to create an account or use the Service.\n- type: business\n  text: If you use the Service wholly for business purposes, then to the extent permitted by law we exclude liability\n    for indirect or consequential loss\nrestricted_uses:\n- summary: Sexual content involving minors\n  text: create sexual content involving\
  \ minors or non-consensual intimate imagery\n- summary: Impersonation of real persons\n  text: impersonate or misleadingly depict a real person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may ask you to verify account or order information where reasonably necessary for security or fraud prevention.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/createprints-ai/eligibility/createprints-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Create Prints's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Art
- Generative AI
- Art Prints
- Print on Demand
- E-Commerce
- Interior Design
- MCP
---
