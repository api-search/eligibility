---
api_specs:
- filename: framethrower-discovery-api-openapi.yml
  format: yaml
  label: FrameThrower Discovery API
  slug: framethrower-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/framethrower/openapi/framethrower-discovery-api-openapi.yml
- filename: framethrower-films-api-openapi.yml
  format: yaml
  label: FrameThrower Films API
  slug: framethrower-films-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/framethrower/openapi/framethrower-films-api-openapi.yml
- filename: framethrower-frames-api-openapi.yml
  format: yaml
  label: FrameThrower Frames API
  slug: framethrower-frames-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/framethrower/openapi/framethrower-frames-api-openapi.yml
- filename: framethrower-search-api-openapi.yml
  format: yaml
  label: FrameThrower Search API
  slug: framethrower-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/framethrower/openapi/framethrower-search-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Section 24 represents that the user is not located in any country or region subject to comprehensive government sanctions.
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you’re using the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: No AI training on frames
    text: training and bulk ingestion are prohibited outright
  - summary: No violating law
    text: Use the Service to violate any law or regulation.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You create an account using your email address or a third-party login (e.g., Google).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: FrameThrower
provenance_date: '2026-11-09'
provider_name: FrameThrower
provider_slug: framethrower
slug: framethrower-eligibility
source_date: '2026-11-09'
source_filename: framethrower-eligibility.yml
source_heading: Eligibility
source_page: https://framethrower.ai/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FrameThrower\naid: framethrower\nurl: https://framethrower.ai/legal/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Section 24 represents that the user is not located in any country or region subject to comprehensive government\n    sanctions.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you’re using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: No AI training on frames\n  text: training\
  \ and bulk ingestion are prohibited outright\n- summary: No violating law\n  text: Use the Service to violate any law or regulation.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You create an account using your email address or a third-party login (e.g., Google).\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/framethrower/eligibility/framethrower-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from FrameThrower's own page on 2026-11-09.
synthetic: false
tags:
- Film
- Cinematography
- Visual Reference
- Image Search
- Media
- Creative Tools
- MCP
- Agent-Native
---
