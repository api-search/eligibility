---
api_specs:
- filename: invoicexml-com-convert-api-openapi.yml
  format: yaml
  label: invoicexml-com Convert API
  slug: invoicexml-com-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-convert-api-openapi.yml
- filename: invoicexml-com-create-api-openapi.yml
  format: yaml
  label: invoicexml-com Create API
  slug: invoicexml-com-create-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-create-api-openapi.yml
- filename: invoicexml-com-embed-api-openapi.yml
  format: yaml
  label: invoicexml-com Embed API
  slug: invoicexml-com-embed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-embed-api-openapi.yml
- filename: invoicexml-com-extract-api-openapi.yml
  format: yaml
  label: invoicexml-com Extract API
  slug: invoicexml-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-extract-api-openapi.yml
- filename: invoicexml-com-home-api-openapi.yml
  format: yaml
  label: invoicexml-com Home API
  slug: invoicexml-com-home-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-home-api-openapi.yml
- filename: invoicexml-com-invoicexml-api-api-openapi.yml
  format: yaml
  label: invoicexml-com Invoice Xml.Api API
  slug: invoicexml-com-invoicexml-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-invoicexml-api-api-openapi.yml
- filename: invoicexml-com-me-api-openapi.yml
  format: yaml
  label: invoicexml-com Me API
  slug: invoicexml-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-me-api-openapi.yml
- filename: invoicexml-com-parse-api-openapi.yml
  format: yaml
  label: invoicexml-com Parse API
  slug: invoicexml-com-parse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-parse-api-openapi.yml
- filename: invoicexml-com-render-api-openapi.yml
  format: yaml
  label: invoicexml-com Render API
  slug: invoicexml-com-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-render-api-openapi.yml
- filename: invoicexml-com-transform-api-openapi.yml
  format: yaml
  label: invoicexml-com Transform API
  slug: invoicexml-com-transform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-transform-api-openapi.yml
- filename: invoicexml-com-validate-api-openapi.yml
  format: yaml
  label: invoicexml-com Validate API
  slug: invoicexml-com-validate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invoicexml-com/openapi/invoicexml-com-validate-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is intended exclusively for businesses, self-employed professionals and other organisations acting in the course of their trade, business, craft or profession. It is not offered to consumers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No third-party document processing
    text: Unless we have agreed otherwise with you in writing, for example in an Enterprise agreement, you may not (a) produce, convert, validate or otherwise process documents on behalf of third parties
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
name: invoicexml-com
provenance_date: '2026-11-09'
provider_name: invoicexml-com
provider_slug: invoicexml-com
slug: invoicexml-com-eligibility
source_date: '2026-11-09'
source_filename: invoicexml-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.invoicexml.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: invoicexml-com\naid: invoicexml-com\nurl: https://www.invoicexml.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The service is intended exclusively for businesses, self-employed professionals and other organisations\n    acting in the course of their trade, business, craft or profession. It is not offered to consumers.\nrestricted_uses:\n- summary: No third-party document processing\n  text: Unless we have agreed otherwise with you in writing, for example in an Enterprise agreement, you may not\n    (a) produce, convert, validate\
  \ or otherwise process documents on behalf of third parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/invoicexml-com/eligibility/invoicexml-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from invoicexml-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Invoicing
- Finance
- Compliance
- European Standards
---
