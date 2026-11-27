---
api_specs:
- filename: pictify-io-batch-api-openapi.yml
  format: yaml
  label: pictify-io Batch API
  slug: pictify-io-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-batch-api-openapi.yml
- filename: pictify-io-bindings-api-openapi.yml
  format: yaml
  label: pictify-io Bindings API
  slug: pictify-io-bindings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-bindings-api-openapi.yml
- filename: pictify-io-gifs-api-openapi.yml
  format: yaml
  label: pictify-io GIFs API
  slug: pictify-io-gifs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-gifs-api-openapi.yml
- filename: pictify-io-images-api-openapi.yml
  format: yaml
  label: pictify-io Images API
  slug: pictify-io-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-images-api-openapi.yml
- filename: pictify-io-pdfs-api-openapi.yml
  format: yaml
  label: pictify-io PDFs API
  slug: pictify-io-pdfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-pdfs-api-openapi.yml
- filename: pictify-io-templates-api-openapi.yml
  format: yaml
  label: pictify-io Templates API
  slug: pictify-io-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-templates-api-openapi.yml
- filename: pictify-io-webhooks-api-openapi.yml
  format: yaml
  label: pictify-io Webhooks API
  slug: pictify-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-webhooks-api-openapi.yml
- filename: pictify-io-gif-api-openapi.yml
  format: yaml
  label: pictify-io Gif API
  slug: pictify-io-gif-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-gif-api-openapi.yml
- filename: pictify-io-image-api-openapi.yml
  format: yaml
  label: pictify-io Image API
  slug: pictify-io-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-image-api-openapi.yml
- filename: pictify-io-pdf-api-openapi.yml
  format: yaml
  label: pictify-io PDF API
  slug: pictify-io-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-pdf-api-openapi.yml
- filename: pictify-io-r-api-openapi.yml
  format: yaml
  label: pictify-io R API
  slug: pictify-io-r-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-r-api-openapi.yml
- filename: pictify-io-video-api-openapi.yml
  format: yaml
  label: pictify-io Video API
  slug: pictify-io-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-video-api-openapi.yml
- filename: pictify-io-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: pictify-io Webhook Subscriptions API
  slug: pictify-io-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pictify-io/openapi/pictify-io-webhook-subscriptions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Service, you represent and warrant that you are at least 18 years of age and have the legal capacity to enter into a binding agreement.
    type: individual
  - text: If you are using our Service on behalf of an entity, you represent and warrant that you have the authority to bind that entity to these terms.
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Illegal or objectionable content
    text: You agree not to generate any Content that is illegal, defamatory, obscene, or otherwise objectionable.
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
name: pictify-io
provenance_date: '2026-11-10'
provider_name: pictify-io
provider_slug: pictify-io
slug: pictify-io-eligibility
source_date: '2026-11-10'
source_filename: pictify-io-eligibility.yml
source_heading: Eligibility
source_page: https://pictify.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pictify-io\naid: pictify-io\nurl: https://pictify.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Service, you represent and warrant that you are at least 18 years of age and have the legal\n    capacity to enter into a binding agreement.\n- type: business\n  text: If you are using our Service on behalf of an entity, you represent and warrant that you have the authority\n    to bind that entity to these terms.\nrestricted_uses:\n- summary: Illegal or objectionable content\n  text: You agree not to generate any\
  \ Content that is illegal, defamatory, obscene, or otherwise objectionable.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/pictify-io/eligibility/pictify-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from pictify-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Templating
- Automation
---
