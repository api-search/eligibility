---
api_specs:
- filename: gist-chat-api-openapi.yml
  format: yaml
  label: Gist Chat API
  slug: gist-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gist/openapi/gist-chat-api-openapi.yml
- filename: gist-health-api-openapi.yml
  format: yaml
  label: Gist Health API
  slug: gist-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gist/openapi/gist-health-api-openapi.yml
- filename: gist-publishers-api-openapi.yml
  format: yaml
  label: Gist Publishers API
  slug: gist-publishers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gist/openapi/gist-publishers-api-openapi.yml
- filename: gist-questions-api-openapi.yml
  format: yaml
  label: Gist Questions API
  slug: gist-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gist/openapi/gist-questions-api-openapi.yml
- filename: gist-root-api-openapi.yml
  format: yaml
  label: Gist Root API
  slug: gist-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gist/openapi/gist-root-api-openapi.yml
- filename: gist-summaries-api-openapi.yml
  format: yaml
  label: Gist Summaries API
  slug: gist-summaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gist/openapi/gist-summaries-api-openapi.yml
- filename: gist-threads-api-openapi.yml
  format: yaml
  label: Gist Threads API
  slug: gist-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gist/openapi/gist-threads-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Services is expressly prohibited from territories where our websites or the Services, or any portion thereof, is illegal.
  entity_types:
  - text: If You have entered into this Agreement on an individual basis, You represent that You are the age of legal majority or older in Your jurisdiction (i.e. 18 and over)
    type: individual
  - text: If You have entered into this Agreement on behalf of a company or other entity, You represent that You are authorized to enter into this Agreement on behalf of that entity
    type: business
  minimum_age:
    text: You must be at least 18 years of age, and, where law requires an older legal age, of legal age for contractual consent or older to use the Services.
    value: '18'
  restricted_uses:
  - summary: Automated decisions with significant effects
    text: make automated decisions producing legal or similarly significant effects on individuals without meaningful human oversight
  - summary: Weapons or malicious software
    text: generate or facilitate the creation of weapons (including CBRN), critical-infrastructure attack tools, or malicious software
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
name: Gist
provenance_date: '2026-11-09'
provider_name: Gist
provider_slug: gist
slug: gist-eligibility
source_date: '2026-11-09'
source_filename: gist-eligibility.yml
source_heading: Eligibility
source_page: https://gist.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gist\naid: gist\nurl: https://gist.ai/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Services is expressly prohibited from territories where our websites or the Services, or any\n    portion thereof, is illegal.\nentity_types:\n- type: individual\n  text: If You have entered into this Agreement on an individual basis, You represent that You are the age of legal\n    majority or older in Your jurisdiction (i.e. 18 and over)\n- type: business\n  text: If You have entered into this Agreement on behalf of a company or other entity, You represent that You are\n\
  \    authorized to enter into this Agreement on behalf of that entity\nrestricted_uses:\n- summary: Automated decisions with significant effects\n  text: make automated decisions producing legal or similarly significant effects on individuals without meaningful\n    human oversight\n- summary: Weapons or malicious software\n  text: generate or facilitate the creation of weapons (including CBRN), critical-infrastructure attack tools, or\n    malicious software\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, and, where law requires an older legal age, of legal age for contractual\n    consent or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/gist/eligibility/gist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Gist's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Advertising
- Marketing
- Brand Visibility
- Publishers
- Search
- Content
- Answer Engine
- Attribution
- Content Licensing
- Media
- RAG
- AdTech
---
