---
api_specs:
- filename: signatureapi-com-deliverables-api-openapi.yml
  format: yaml
  label: signatureapi-com Deliverables API
  slug: signatureapi-com-deliverables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signatureapi-com/openapi/signatureapi-com-deliverables-api-openapi.yml
- filename: signatureapi-com-envelopes-api-openapi.yml
  format: yaml
  label: signatureapi-com Envelopes API
  slug: signatureapi-com-envelopes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signatureapi-com/openapi/signatureapi-com-envelopes-api-openapi.yml
- filename: signatureapi-com-events-api-openapi.yml
  format: yaml
  label: signatureapi-com Events API
  slug: signatureapi-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signatureapi-com/openapi/signatureapi-com-events-api-openapi.yml
- filename: signatureapi-com-recipients-api-openapi.yml
  format: yaml
  label: signatureapi-com Recipients API
  slug: signatureapi-com-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signatureapi-com/openapi/signatureapi-com-recipients-api-openapi.yml
- filename: signatureapi-com-senders-api-openapi.yml
  format: yaml
  label: signatureapi-com Senders API
  slug: signatureapi-com-senders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signatureapi-com/openapi/signatureapi-com-senders-api-openapi.yml
- filename: signatureapi-com-uploads-api-openapi.yml
  format: yaml
  label: signatureapi-com Uploads API
  slug: signatureapi-com-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signatureapi-com/openapi/signatureapi-com-uploads-api-openapi.yml
- filename: signatureapi-com-webhooks-api-openapi.yml
  format: yaml
  label: signatureapi-com Webhooks API
  slug: signatureapi-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/signatureapi-com/openapi/signatureapi-com-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The party agreeing to these Terms and/or paying to use the Service is known as “you” or “user.”
    type: business
  minimum_age:
    text: you guarantee that you are at or above the age of 18
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: use the Service for any unlawful purpose or for the promotion of illegal activities
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
name: signatureapi-com
provenance_date: '2026-11-10'
provider_name: signatureapi-com
provider_slug: signatureapi-com
slug: signatureapi-com-eligibility
source_date: '2026-11-10'
source_filename: signatureapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://signatureapi.com/docs/legal/terms/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: signatureapi-com\naid: signatureapi-com\nurl: https://signatureapi.com/docs/legal/terms/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The party agreeing to these Terms and/or paying to use the Service is known as “you” or “user.”\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: use the Service for any unlawful purpose or for the promotion of illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you guarantee that you are at or above\
  \ the age of 18\n"
source_yaml_url: https://artifacts.apis.io/signatureapi-com/eligibility/signatureapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from signatureapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Signature
- Software-as-a-Service
- Compliance
- Automation
---
