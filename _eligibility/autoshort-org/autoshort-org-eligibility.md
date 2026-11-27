---
api_specs:
- filename: autoshort-org-account-api-openapi.yml
  format: yaml
  label: AutoShort Account API
  slug: autoshort-org-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-account-api-openapi.yml
- filename: autoshort-org-catalog-api-openapi.yml
  format: yaml
  label: AutoShort Catalog API
  slug: autoshort-org-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-catalog-api-openapi.yml
- filename: autoshort-org-drafts-api-openapi.yml
  format: yaml
  label: AutoShort Drafts API
  slug: autoshort-org-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-drafts-api-openapi.yml
- filename: autoshort-org-motion-api-openapi.yml
  format: yaml
  label: AutoShort Motion API
  slug: autoshort-org-motion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-motion-api-openapi.yml
- filename: autoshort-org-pay-per-call-x402-api-openapi.yml
  format: yaml
  label: AutoShort Pay per call (x402) API
  slug: autoshort-org-pay-per-call-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-pay-per-call-x402-api-openapi.yml
- filename: autoshort-org-series-api-openapi.yml
  format: yaml
  label: AutoShort Series API
  slug: autoshort-org-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-series-api-openapi.yml
- filename: autoshort-org-videos-api-openapi.yml
  format: yaml
  label: AutoShort Videos API
  slug: autoshort-org-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-videos-api-openapi.yml
- filename: autoshort-org-webhooks-api-openapi.yml
  format: yaml
  label: AutoShort Webhooks API
  slug: autoshort-org-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use our service.
    value: '13'
  restricted_uses:
  - summary: Unauthorized likeness or deepfakes
    text: Use a person's likeness or voice without authorization, or impersonate a person without their informed consent
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
name: AutoShort
provenance_date: '2026-11-09'
provider_name: AutoShort
provider_slug: autoshort-org
slug: autoshort-org-eligibility
source_date: '2026-11-09'
source_filename: autoshort-org-eligibility.yml
source_heading: Eligibility
source_page: https://autoshort.org/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AutoShort\naid: autoshort-org\nurl: https://autoshort.org/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unauthorized likeness or deepfakes\n  text: Use a person's likeness or voice without authorization, or impersonate a person without their informed consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use our service.\n"
source_yaml_url: https://artifacts.apis.io/autoshort-org/eligibility/autoshort-org-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from AutoShort's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video Generation
- YouTube Shorts
- Automation
- Faceless Content
---
