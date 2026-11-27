---
api_specs:
- filename: kymaapi-com-audio-api-openapi.yml
  format: yaml
  label: kymaapi-com Audio API
  slug: kymaapi-com-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-audio-api-openapi.yml
- filename: kymaapi-com-auth-api-openapi.yml
  format: yaml
  label: kymaapi-com Auth API
  slug: kymaapi-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-auth-api-openapi.yml
- filename: kymaapi-com-chat-api-openapi.yml
  format: yaml
  label: kymaapi-com Chat API
  slug: kymaapi-com-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-chat-api-openapi.yml
- filename: kymaapi-com-completions-api-openapi.yml
  format: yaml
  label: kymaapi-com Completions API
  slug: kymaapi-com-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-completions-api-openapi.yml
- filename: kymaapi-com-credits-api-openapi.yml
  format: yaml
  label: kymaapi-com Credits API
  slug: kymaapi-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-credits-api-openapi.yml
- filename: kymaapi-com-decisions-api-openapi.yml
  format: yaml
  label: kymaapi-com Decisions API
  slug: kymaapi-com-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-decisions-api-openapi.yml
- filename: kymaapi-com-discovery-api-openapi.yml
  format: yaml
  label: kymaapi-com Discovery API
  slug: kymaapi-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-discovery-api-openapi.yml
- filename: kymaapi-com-embeddings-api-openapi.yml
  format: yaml
  label: kymaapi-com Embeddings API
  slug: kymaapi-com-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-embeddings-api-openapi.yml
- filename: kymaapi-com-images-api-openapi.yml
  format: yaml
  label: kymaapi-com Images API
  slug: kymaapi-com-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-images-api-openapi.yml
- filename: kymaapi-com-models-api-openapi.yml
  format: yaml
  label: kymaapi-com Models API
  slug: kymaapi-com-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-models-api-openapi.yml
- filename: kymaapi-com-video-api-openapi.yml
  format: yaml
  label: kymaapi-com Video API
  slug: kymaapi-com-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-video-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not be located in a country subject to a U.S. government embargo, and you must not be on any U.S. government list of prohibited or restricted parties.
  entity_types:
  - text: You must be at least 13 years old to use Kyma at all. If you are under 18, you confirm a parent or legal guardian has reviewed and accepted these terms on your behalf.
    type: individual
  - text: If you are using Kyma on behalf of a company or other organization, you confirm you have authority to bind that organization to these terms.
    type: business
  minimum_age:
    text: You must be at least 13 years old to use Kyma at all.
    value: '13'
  restricted_uses:
  - summary: Prohibited content categories
    text: The AUP lists categories of content and behavior that are not allowed — including child sexual abuse material, non-consensual intimate imagery, deepfakes of real people without consent, election manipulation, and other categories.
  - summary: High-stakes decisions
    text: Do not rely on Outputs in any high-stakes decision (medical diagnosis, legal action, financial trade, safety-critical control loop, infrastructure operation) without independent professional review.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Register with a valid email to get your API key. Provide accurate information and keep it current.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: kymaapi-com
provenance_date: '2026-11-09'
provider_name: kymaapi-com
provider_slug: kymaapi-com
slug: kymaapi-com-eligibility
source_date: '2026-11-09'
source_filename: kymaapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://kymaapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kymaapi-com\naid: kymaapi-com\nurl: https://kymaapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not be located in a country subject to a U.S. government embargo, and you must not be on any U.S.\n    government list of prohibited or restricted parties.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use Kyma at all. If you are under 18, you confirm a parent or legal\n    guardian has reviewed and accepted these terms on your behalf.\n- type: business\n  text: If you are using Kyma on behalf of a company or other organization,\
  \ you confirm you have authority to bind\n    that organization to these terms.\nrestricted_uses:\n- summary: Prohibited content categories\n  text: The AUP lists categories of content and behavior that are not allowed — including child sexual abuse material,\n    non-consensual intimate imagery, deepfakes of real people without consent, election manipulation, and other\n    categories.\n- summary: High-stakes decisions\n  text: Do not rely on Outputs in any high-stakes decision (medical diagnosis, legal action, financial trade, safety-critical\n    control loop, infrastructure operation) without independent professional review.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Register with a valid email to get your API key. Provide accurate information and keep it current.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use Kyma at all.\n"
source_yaml_url: https://artifacts.apis.io/kymaapi-com/eligibility/kymaapi-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from kymaapi-com's own page on 2026-11-09.
synthetic: false
tags:
- LLM
- API Gateway
- Artificial Intelligence
- Machine Learning
- Developer Tools
---
