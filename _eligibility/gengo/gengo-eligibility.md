---
api_specs:
- filename: gengo-account-api-openapi.yml
  format: yaml
  label: Gengo Account API
  slug: gengo-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gengo/openapi/gengo-account-api-openapi.yml
- filename: gengo-glossary-api-openapi.yml
  format: yaml
  label: Gengo Glossary API
  slug: gengo-glossary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gengo/openapi/gengo-glossary-api-openapi.yml
- filename: gengo-job-api-openapi.yml
  format: yaml
  label: Gengo Job API
  slug: gengo-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gengo/openapi/gengo-job-api-openapi.yml
- filename: gengo-jobs-api-openapi.yml
  format: yaml
  label: Gengo Jobs API
  slug: gengo-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gengo/openapi/gengo-jobs-api-openapi.yml
- filename: gengo-order-api-openapi.yml
  format: yaml
  label: Gengo Order API
  slug: gengo-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gengo/openapi/gengo-order-api-openapi.yml
- filename: gengo-service-api-openapi.yml
  format: yaml
  label: Gengo Service API
  slug: gengo-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gengo/openapi/gengo-service-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are 18 years of age, or of the age of majority in your place of residence or jurisdiction.
    type: individual
  - text: If You are entering into this TOS on behalf of a company or other legal entity, You represent that You have the legal authority to bind the legal entity to this TOS, in which case “You” or “Your” means that entity.
    type: business
  minimum_age:
    text: You represent that you are 18 years of age, or of the age of majority in your place of residence or jurisdiction.
    value: '18'
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
name: Gengo
provenance_date: '2026-11-09'
provider_name: Gengo
provider_slug: gengo
slug: gengo-eligibility
source_date: '2026-11-09'
source_filename: gengo-eligibility.yml
source_heading: Eligibility
source_page: https://gengo.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gengo\naid: gengo\nurl: https://gengo.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are 18 years of age, or of the age of majority in your place of residence or jurisdiction.\n- type: business\n  text: If You are entering into this TOS on behalf of a company or other legal entity, You represent that You have\n    the legal authority to bind the legal entity to this TOS, in which case “You” or “Your” means that entity.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are 18 years of age, or of the age of majority in your place of residence or jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/gengo/eligibility/gengo-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Gengo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Translation
- Localization
- Human Translation
- Language Services
- Internationalization
- Content
- Text
---
