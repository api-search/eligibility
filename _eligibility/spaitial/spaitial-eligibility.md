---
api_specs:
- filename: spaitial-files-api-openapi.yml
  format: yaml
  label: SpAItial Files API
  slug: spaitial-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spaitial/openapi/spaitial-files-api-openapi.yml
- filename: spaitial-models-api-openapi.yml
  format: yaml
  label: SpAItial Models API
  slug: spaitial-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spaitial/openapi/spaitial-models-api-openapi.yml
- filename: spaitial-panoramas-api-openapi.yml
  format: yaml
  label: SpAItial Panoramas API
  slug: spaitial-panoramas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spaitial/openapi/spaitial-panoramas-api-openapi.yml
- filename: spaitial-worlds-api-openapi.yml
  format: yaml
  label: SpAItial Worlds API
  slug: spaitial-worlds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spaitial/openapi/spaitial-worlds-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: SpAItial is based in Europe and provides Services globally, including to users in the United States, subject to applicable law.
  entity_types:
  - text: 'If the User is accepting these Terms on behalf of an organisation, the User represents that: (i) it agrees, on behalf of that organisation, to these Terms'
    type: business
  - text: The Services are intended for use only by individuals who are at least eighteen (18) years of age.
    type: individual
  minimum_age:
    text: The Services are intended for use only by individuals who are at least eighteen (18) years of age.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful content
    text: to generate content that is unlawful, defamatory, obscene, threatening, harassing, discriminatory, or otherwise harmful
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
name: SpAItial
provenance_date: '2026-11-10'
provider_name: SpAItial
provider_slug: spaitial
slug: spaitial-eligibility
source_date: '2026-11-10'
source_filename: spaitial-eligibility.yml
source_heading: Eligibility
source_page: https://spaitial.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SpAItial\naid: spaitial\nurl: https://spaitial.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: SpAItial is based in Europe and provides Services globally, including to users in the United States, subject\n    to applicable law.\nentity_types:\n- type: business\n  text: 'If the User is accepting these Terms on behalf of an organisation, the User represents that: (i) it agrees,\n    on behalf of that organisation, to these Terms'\n- type: individual\n  text: The Services are intended for use only by individuals who are at least eighteen (18) years of age.\nrestricted_uses:\n\
  - summary: Unlawful or harmful content\n  text: to generate content that is unlawful, defamatory, obscene, threatening, harassing, discriminatory, or otherwise\n    harmful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for use only by individuals who are at least eighteen (18) years of age.\n"
source_yaml_url: https://artifacts.apis.io/spaitial/eligibility/spaitial-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from SpAItial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Spatial AI
- World Models
- 3D
- Gaussian Splatting
- Generative AI
- Developer API
- MCP
---
