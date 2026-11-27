---
api_specs:
- filename: namegender-account-api-openapi.yml
  format: yaml
  label: NameGender Account API
  slug: namegender-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-account-api-openapi.yml
- filename: namegender-batches-api-openapi.yml
  format: yaml
  label: NameGender Batches API
  slug: namegender-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-batches-api-openapi.yml
- filename: namegender-gender-api-openapi.yml
  format: yaml
  label: NameGender Gender API
  slug: namegender-gender-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-gender-api-openapi.yml
- filename: namegender-webhooks-api-openapi.yml
  format: yaml
  label: NameGender Webhooks API
  slug: namegender-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/namegender/openapi/namegender-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use NameGender for an organisation, you confirm that you can accept these terms for that organisation.
    type: business
  - text: You must be legally able to enter into a binding agreement.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sole basis for significant decisions
    text: Do not use a result as the sole basis for employment, credit, housing, healthcare, education, insurance, law enforcement or another decision that produces a legal or similarly significant effect.
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
name: NameGender
provenance_date: '2026-11-10'
provider_name: NameGender
provider_slug: namegender
slug: namegender-eligibility
source_date: '2026-11-10'
source_filename: namegender-eligibility.yml
source_heading: Eligibility
source_page: https://namegender.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NameGender\naid: namegender\nurl: https://namegender.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use NameGender for an organisation, you confirm that you can accept these terms for that organisation.\n- type: individual\n  text: You must be legally able to enter into a binding agreement.\nrestricted_uses:\n- summary: Sole basis for significant decisions\n  text: Do not use a result as the sole basis for employment, credit, housing, healthcare, education, insurance,\n    law enforcement or another decision that produces\
  \ a legal or similarly significant effect.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/namegender/eligibility/namegender-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from NameGender's own page on 2026-11-10.
synthetic: false
tags:
- Gender
- Name
- Data Enrichment
- Demographics
- Bulk
---
