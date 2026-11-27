---
api_specs:
- filename: pimloc-account-api-openapi.yml
  format: yaml
  label: Pimloc Account API
  slug: pimloc-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-account-api-openapi.yml
- filename: pimloc-authentication-api-openapi.yml
  format: yaml
  label: Pimloc Authentication API
  slug: pimloc-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-authentication-api-openapi.yml
- filename: pimloc-media-api-openapi.yml
  format: yaml
  label: Pimloc Media API
  slug: pimloc-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-media-api-openapi.yml
- filename: pimloc-projects-api-openapi.yml
  format: yaml
  label: Pimloc Projects API
  slug: pimloc-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-projects-api-openapi.yml
- filename: pimloc-secure-redact-api-api-openapi.yml
  format: yaml
  label: Pimloc Secure Redact API
  slug: pimloc-secure-redact-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pimloc/openapi/pimloc-secure-redact-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'End User: the individual or entity subscribing for a User Subscription to use the Services in accordance with these Terms.'
    type: individual
  - text: 'End User: the individual or entity subscribing for a User Subscription to use the Services in accordance with these Terms.'
    type: business
  minimum_age:
    text: (1) REPRESENT THAT YOU ARE OF THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION
    value: null
  restricted_uses:
  - summary: Unlawful or harmful material
    text: 'The End User shall not access, store, distribute or transmit any Viruses, or any material during the course of its use of the Services that: (a) is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing'
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
name: Pimloc
provenance_date: '2026-11-10'
provider_name: Pimloc
provider_slug: pimloc
slug: pimloc-eligibility
source_date: '2026-11-10'
source_filename: pimloc-eligibility.yml
source_heading: Eligibility
source_page: https://www.secureredact.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pimloc\naid: pimloc\nurl: https://www.secureredact.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'End User: the individual or entity subscribing for a User Subscription to use the Services in accordance\n    with these Terms.'\n- type: business\n  text: 'End User: the individual or entity subscribing for a User Subscription to use the Services in accordance\n    with these Terms.'\nrestricted_uses:\n- summary: Unlawful or harmful material\n  text: 'The End User shall not access, store, distribute or transmit any\
  \ Viruses, or any material during the course\n    of its use of the Services that: (a) is unlawful, harmful, threatening, defamatory, obscene, infringing, harassing'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: (1) REPRESENT THAT YOU ARE OF THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION\n"
source_yaml_url: https://artifacts.apis.io/pimloc/eligibility/pimloc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pimloc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Privacy
- Video Redaction
- Anonymization
- PII
- Data Protection
- Artificial Intelligence
- Compliance
- Video Analytics
---
