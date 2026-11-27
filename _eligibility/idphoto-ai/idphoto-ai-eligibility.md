---
api_specs:
- filename: idphoto-ai-id-photo-api-v1-api-openapi.yml
  format: yaml
  label: idphoto-ai ID Photo API V1 API
  slug: idphoto-ai-id-photo-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idphoto-ai/openapi/idphoto-ai-id-photo-api-v1-api-openapi.yml
- filename: idphoto-ai-id-photo-api-v2-api-openapi.yml
  format: yaml
  label: idphoto-ai ID Photo API V2 API
  slug: idphoto-ai-id-photo-api-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idphoto-ai/openapi/idphoto-ai-id-photo-api-v2-api-openapi.yml
- filename: idphoto-ai-misc-api-openapi.yml
  format: yaml
  label: idphoto-ai Misc API
  slug: idphoto-ai-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idphoto-ai/openapi/idphoto-ai-misc-api-openapi.yml
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
  - summary: No guaranteed document acceptance claims
    text: Do not tell your users the document will be issued because the file looks right.
  - summary: No digital alteration of US/UK passports
    text: US and UK passport photographs must not be digitally altered.
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
name: idphoto-ai
provenance_date: '2026-11-09'
provider_name: idphoto-ai
provider_slug: idphoto-ai
slug: idphoto-ai-eligibility
source_date: '2026-11-09'
source_filename: idphoto-ai-eligibility.yml
source_heading: Eligibility
source_page: https://idphoto.ai/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: idphoto-ai\naid: idphoto-ai\nurl: https://idphoto.ai/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No guaranteed document acceptance claims\n  text: Do not tell your users the document will be issued because the file looks right.\n- summary: No digital alteration of US/UK passports\n  text: US and UK passport photographs must not be digitally altered.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/idphoto-ai/eligibility/idphoto-ai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from idphoto-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Photos
- Identity
- Passport
- Visa
- Image Processing
---
