---
api_specs:
- filename: misoai-ask-apis-api-openapi.yml
  format: yaml
  label: miso.ai Ask APIs API
  slug: misoai-ask-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-ask-apis-api-openapi.yml
- filename: misoai-bulk-api-api-openapi.yml
  format: yaml
  label: miso.ai Bulk API
  slug: misoai-bulk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-bulk-api-api-openapi.yml
- filename: misoai-experiment-apis-api-openapi.yml
  format: yaml
  label: miso.ai Experiment APIs API
  slug: misoai-experiment-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-experiment-apis-api-openapi.yml
- filename: misoai-interaction-apis-api-openapi.yml
  format: yaml
  label: miso.ai Interaction APIs API
  slug: misoai-interaction-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-interaction-apis-api-openapi.yml
- filename: misoai-product-content-apis-api-openapi.yml
  format: yaml
  label: miso.ai Product / Content APIs API
  slug: misoai-product-content-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-product-content-apis-api-openapi.yml
- filename: misoai-product-recommendations-api-openapi.yml
  format: yaml
  label: miso.ai Product Recommendations API
  slug: misoai-product-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-product-recommendations-api-openapi.yml
- filename: misoai-q-a-apis-api-openapi.yml
  format: yaml
  label: miso.ai Q&A APIs API
  slug: misoai-q-a-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-q-a-apis-api-openapi.yml
- filename: misoai-search-apis-api-openapi.yml
  format: yaml
  label: miso.ai Search APIs API
  slug: misoai-search-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-search-apis-api-openapi.yml
- filename: misoai-user-apis-api-openapi.yml
  format: yaml
  label: miso.ai User APIs API
  slug: misoai-user-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-user-apis-api-openapi.yml
- filename: misoai-user-recommendations-api-openapi.yml
  format: yaml
  label: miso.ai User Recommendations API
  slug: misoai-user-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/misoai/openapi/misoai-user-recommendations-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “ Users ” individuals who engage with the Services.
    type: individual
  - text: “ Customer ” as the individual or organization who has purchased the Miso Services and integrated them into their products and services.
    type: other
  minimum_age:
    text: You affirm that you are over the age of 13, as the Services are not intended for children under 13.
    value: '13'
  restricted_uses:
  - summary: Competitive analysis or competing product
    text: access or use the Site or the Services for purposes of competitive analysis of the Site or the Services, the development, provision or use of a competing software service or product
  - summary: Automated access exceeding human rate
    text: use or launch any automated system, including, without limitation, “robots,” “spiders,” or “offline readers,” that accesses the Site or the Services in a manner that sends more request messages to the Miso Systems in a given period of time than a human can reasonably produce in the same period
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
name: miso.ai
provenance_date: '2026-11-10'
provider_name: miso.ai
provider_slug: misoai
slug: misoai-eligibility
source_date: '2026-11-10'
source_filename: misoai-eligibility.yml
source_heading: Eligibility
source_page: https://miso.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: miso.ai\naid: misoai\nurl: https://miso.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “ Users ” individuals who engage with the Services.\n- type: other\n  text: “ Customer ” as the individual or organization who has purchased the Miso Services and integrated them into\n    their products and services.\nrestricted_uses:\n- summary: Competitive analysis or competing product\n  text: access or use the Site or the Services for purposes of competitive analysis of the Site or the Services,\n    the development, provision\
  \ or use of a competing software service or product\n- summary: Automated access exceeding human rate\n  text: use or launch any automated system, including, without limitation, “robots,” “spiders,” or “offline readers,”\n    that accesses the Site or the Services in a manner that sends more request messages to the Miso Systems in a\n    given period of time than a human can reasonably produce in the same period\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You affirm that you are over the age of 13, as the Services are not intended for children under 13.\n"
source_yaml_url: https://artifacts.apis.io/misoai/eligibility/misoai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from miso.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Search
- Recommendations
- Personalization
- Semantic Search
- LLM
- Question Answering
- Publishing
- Media
- Retail
- E-Commerce
- Developers
---
