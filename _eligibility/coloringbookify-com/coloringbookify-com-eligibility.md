---
api_specs:
- filename: coloringbookify-com-account-api-openapi.yml
  format: yaml
  label: ColoringBookify Account API
  slug: coloringbookify-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-account-api-openapi.yml
- filename: coloringbookify-com-books-api-openapi.yml
  format: yaml
  label: ColoringBookify Books API
  slug: coloringbookify-com-books-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-books-api-openapi.yml
- filename: coloringbookify-com-characters-api-openapi.yml
  format: yaml
  label: ColoringBookify Characters API
  slug: coloringbookify-com-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-characters-api-openapi.yml
- filename: coloringbookify-com-operations-api-openapi.yml
  format: yaml
  label: ColoringBookify Operations API
  slug: coloringbookify-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-operations-api-openapi.yml
- filename: coloringbookify-com-pages-api-openapi.yml
  format: yaml
  label: ColoringBookify Pages API
  slug: coloringbookify-com-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-pages-api-openapi.yml
- filename: coloringbookify-com-planning-api-openapi.yml
  format: yaml
  label: ColoringBookify Planning API
  slug: coloringbookify-com-planning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-planning-api-openapi.yml
- filename: coloringbookify-com-print-api-openapi.yml
  format: yaml
  label: ColoringBookify Print API
  slug: coloringbookify-com-print-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coloringbookify-com/openapi/coloringbookify-com-print-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Business plans include the commercial-use permission described in our Commercial Use guidance for eligible outputs created while the Business plan is active.
    type: business
  minimum_age:
    text: The service is not directed to children who cannot consent to online services on their own.
    value: null
  restricted_uses:
  - summary: Prohibited content
    text: You may not upload, request, create, edit, store, publish, or distribute the following content through ColoringBookify.
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
name: ColoringBookify
provenance_date: '2026-11-09'
provider_name: ColoringBookify
provider_slug: coloringbookify-com
slug: coloringbookify-com-eligibility
source_date: '2026-11-09'
source_filename: coloringbookify-com-eligibility.yml
source_heading: Eligibility
source_page: https://coloringbookify.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ColoringBookify\naid: coloringbookify-com\nurl: https://coloringbookify.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Business plans include the commercial-use permission described in our Commercial Use guidance for eligible\n    outputs created while the Business plan is active.\nrestricted_uses:\n- summary: Prohibited content\n  text: You may not upload, request, create, edit, store, publish, or distribute the following content through ColoringBookify.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: The service is not directed to children who cannot consent to online services on their own.\n"
source_yaml_url: https://artifacts.apis.io/coloringbookify-com/eligibility/coloringbookify-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ColoringBookify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Coloring Books
- Image Generation
- PDF Generation
- Printing
- Publishing
- MCP
---
