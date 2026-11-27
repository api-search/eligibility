---
api_specs:
- filename: clickpost-cancellation-api-openapi.yml
  format: yaml
  label: ClickPost Cancellation API
  slug: clickpost-cancellation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickpost/openapi/clickpost-cancellation-api-openapi.yml
- filename: clickpost-label-api-openapi.yml
  format: yaml
  label: ClickPost Label API
  slug: clickpost-label-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickpost/openapi/clickpost-label-api-openapi.yml
- filename: clickpost-order-api-openapi.yml
  format: yaml
  label: ClickPost Order API
  slug: clickpost-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickpost/openapi/clickpost-order-api-openapi.yml
- filename: clickpost-pickup-api-openapi.yml
  format: yaml
  label: ClickPost Pickup API
  slug: clickpost-pickup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickpost/openapi/clickpost-pickup-api-openapi.yml
- filename: clickpost-recommendation-api-openapi.yml
  format: yaml
  label: ClickPost Recommendation API
  slug: clickpost-recommendation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickpost/openapi/clickpost-recommendation-api-openapi.yml
- filename: clickpost-serviceability-api-openapi.yml
  format: yaml
  label: ClickPost Serviceability API
  slug: clickpost-serviceability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickpost/openapi/clickpost-serviceability-api-openapi.yml
- filename: clickpost-tracking-api-openapi.yml
  format: yaml
  label: ClickPost Tracking API
  slug: clickpost-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clickpost/openapi/clickpost-tracking-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you must be an adult (of 18 years and above) to register on our website and use our services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive content
    text: The user agrees not to publish any material on the website or our associated applications that is defamatory, offensive, abusive, indecent or needlessly distressful to any person and shall refrain from advertising their goods/services.
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
name: ClickPost
provenance_date: '2026-11-09'
provider_name: ClickPost
provider_slug: clickpost
slug: clickpost-eligibility
source_date: '2026-11-09'
source_filename: clickpost-eligibility.yml
source_heading: Eligibility
source_page: https://www.clickpost.ai/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClickPost\naid: clickpost\nurl: https://www.clickpost.ai/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or abusive content\n  text: The user agrees not to publish any material on the website or our associated applications that is defamatory,\n    offensive, abusive, indecent or needlessly distressful to any person and shall refrain from advertising their\n    goods/services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you\
  \ must be an adult (of 18 years and above) to register on our website and use our services.\n"
source_yaml_url: https://artifacts.apis.io/clickpost/eligibility/clickpost-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from ClickPost's own page on 2026-11-09.
synthetic: false
tags:
- Carrier
- Delivery
- E-commerce Logistics
- Logistics
- Returns
- Shipping
- Supply Chain
- Tracking
---
