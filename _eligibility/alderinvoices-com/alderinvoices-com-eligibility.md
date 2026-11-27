---
api_specs:
- filename: alderinvoices-com-drafts-api-openapi.yml
  format: yaml
  label: Alder Drafts API
  slug: alderinvoices-com-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alderinvoices-com/openapi/alderinvoices-com-drafts-api-openapi.yml
- filename: alderinvoices-com-pdf-api-openapi.yml
  format: yaml
  label: Alder PDF API
  slug: alderinvoices-com-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alderinvoices-com/openapi/alderinvoices-com-pdf-api-openapi.yml
- filename: alderinvoices-com-template-drafts-api-openapi.yml
  format: yaml
  label: Alder Template Drafts API
  slug: alderinvoices-com-template-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alderinvoices-com/openapi/alderinvoices-com-template-drafts-api-openapi.yml
- filename: alderinvoices-com-templates-api-openapi.yml
  format: yaml
  label: Alder Templates API
  slug: alderinvoices-com-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alderinvoices-com/openapi/alderinvoices-com-templates-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use it for a business, you agree on that business's behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Real goods or services only
    text: Only bill for real goods or services, and only add customer details you are allowed to share with a service provider.
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
name: Alder
provenance_date: '2026-11-09'
provider_name: Alder
provider_slug: alderinvoices-com
slug: alderinvoices-com-eligibility
source_date: '2026-11-09'
source_filename: alderinvoices-com-eligibility.yml
source_heading: Eligibility
source_page: https://alderinvoices.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alder\naid: alderinvoices-com\nurl: https://alderinvoices.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use it for a business, you agree on that business's behalf.\nrestricted_uses:\n- summary: Real goods or services only\n  text: Only bill for real goods or services, and only add customer details you are allowed to share with a service\n    provider.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alderinvoices-com/eligibility/alderinvoices-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Alder's own page on 2026-11-09.
synthetic: false
tags:
- Invoices
- Finance
- PDF
- Free
- MCP
---
