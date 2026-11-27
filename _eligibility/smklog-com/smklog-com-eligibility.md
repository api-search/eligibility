---
api_specs:
- filename: smklog-com-operations-api-openapi.yml
  format: yaml
  label: SMKlog Operations API
  slug: smklog-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-operations-api-openapi.yml
- filename: smklog-com-dimensional-weight-api-openapi.yml
  format: yaml
  label: SMKlog Dimensional Weight API
  slug: smklog-com-dimensional-weight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-dimensional-weight-api-openapi.yml
- filename: smklog-com-holiday-shipping-api-openapi.yml
  format: yaml
  label: SMKlog Holiday Shipping API
  slug: smklog-com-holiday-shipping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-holiday-shipping-api-openapi.yml
- filename: smklog-com-payments-api-openapi.yml
  format: yaml
  label: SMKlog Payments API
  slug: smklog-com-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-payments-api-openapi.yml
- filename: smklog-com-price-index-api-openapi.yml
  format: yaml
  label: SMKlog Price Index API
  slug: smklog-com-price-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-price-index-api-openapi.yml
- filename: smklog-com-refunds-api-openapi.yml
  format: yaml
  label: SMKlog Refunds API
  slug: smklog-com-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-refunds-api-openapi.yml
- filename: smklog-com-shipping-rates-api-openapi.yml
  format: yaml
  label: SMKlog Shipping Rates API
  slug: smklog-com-shipping-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-shipping-rates-api-openapi.yml
- filename: smklog-com-shipping-restrictions-api-openapi.yml
  format: yaml
  label: SMKlog Shipping Restrictions API
  slug: smklog-com-shipping-restrictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-shipping-restrictions-api-openapi.yml
- filename: smklog-com-tracking-api-openapi.yml
  format: yaml
  label: SMKlog Tracking API
  slug: smklog-com-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-tracking-api-openapi.yml
- filename: smklog-com-webhooks-api-openapi.yml
  format: yaml
  label: SMKlog Webhooks API
  slug: smklog-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smklog-com/openapi/smklog-com-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    - GB
    - DE
    - AU
    text: for US domestic shipments and for international shipments from the US to supported destinations (currently Canada, the UK, Germany and Australia)
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if that is higher
    value: '18'
  restricted_uses:
  - summary: Restricted or prohibited shipment contents
    text: You are responsible for ensuring that your shipment does not contain prohibited, restricted, hazardous, misdeclared, or unlawful items.
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
name: SMKlog
provenance_date: '2026-11-10'
provider_name: SMKlog
provider_slug: smklog-com
slug: smklog-com-eligibility
source_date: '2026-11-10'
source_filename: smklog-com-eligibility.yml
source_heading: Eligibility
source_page: https://smklog.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SMKlog\naid: smklog-com\nurl: https://smklog.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  - GB\n  - DE\n  - AU\n  excluded: []\n  text: for US domestic shipments and for international shipments from the US to supported destinations (currently\n    Canada, the UK, Germany and Australia)\nentity_types: []\nrestricted_uses:\n- summary: Restricted or prohibited shipment contents\n  text: You are responsible for ensuring that your shipment does not contain prohibited, restricted, hazardous,\n    misdeclared, or unlawful items.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live if that is higher\n"
source_yaml_url: https://artifacts.apis.io/smklog-com/eligibility/smklog-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SMKlog's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Shipping
- Logistics
- Parcel Shipping
- shipping-rates
- Shipping Labels
- E-Commerce
- Agents
- MCP
- A2A
---
