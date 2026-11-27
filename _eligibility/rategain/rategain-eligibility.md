---
api_specs:
- filename: rategain-developer-portal-api-openapi.yml
  format: yaml
  label: RateGain Developer Portal API
  slug: rategain-developer-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rategain/openapi/rategain-developer-portal-api-openapi.yml
- filename: rategain-our-products-api-openapi.yml
  format: yaml
  label: RateGain Our Products API
  slug: rategain-our-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rategain/openapi/rategain-our-products-api-openapi.yml
- filename: rategain-ultradirect-api-openapi.yml
  format: yaml
  label: RateGain Ultradirect API
  slug: rategain-ultradirect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rategain/openapi/rategain-ultradirect-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive content
    text: Post/upload content or initiate communication which are unlawful, obscene, discriminatory, libelous, abusive or otherwise objectionable
  - summary: Collecting other users' data
    text: Collect or store personal data and content of other Users/Members
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
name: RateGain
provenance_date: '2026-11-10'
provider_name: RateGain
provider_slug: rategain
slug: rategain-eligibility
source_date: '2026-11-10'
source_filename: rategain-eligibility.yml
source_heading: Eligibility
source_page: https://rategain.com/terms-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RateGain\naid: rategain\nurl: https://rategain.com/terms-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or abusive content\n  text: Post/upload content or initiate communication which are unlawful, obscene, discriminatory, libelous, abusive\n    or otherwise objectionable\n- summary: Collecting other users' data\n  text: Collect or store personal data and content of other Users/Members\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rategain/eligibility/rategain-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from RateGain's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hospitality
- TravelTech
- Software-as-a-Service
- Revenue Management
---
