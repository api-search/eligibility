---
api_specs:
- filename: cheap409a-com-enquiry-api-openapi.yml
  format: yaml
  label: Cheap 409A Enquiry API
  slug: cheap409a-com-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cheap409a-com/openapi/cheap409a-com-enquiry-api-openapi.yml
- filename: cheap409a-com-guide-api-openapi.yml
  format: yaml
  label: Cheap 409A Guide API
  slug: cheap409a-com-guide-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cheap409a-com/openapi/cheap409a-com-guide-api-openapi.yml
- filename: cheap409a-com-mcp-api-openapi.yml
  format: yaml
  label: Cheap 409A MCP API
  slug: cheap409a-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cheap409a-com/openapi/cheap409a-com-mcp-api-openapi.yml
claim_count: 1
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
  - summary: Not tax, legal or valuation advice
    text: Nothing on it is tax, legal or valuation advice, and it is not a substitute for an independent appraisal
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
name: Cheap 409A
provenance_date: '2026-11-09'
provider_name: Cheap 409A
provider_slug: cheap409a-com
slug: cheap409a-com-eligibility
source_date: '2026-11-09'
source_filename: cheap409a-com-eligibility.yml
source_heading: Eligibility
source_page: https://cheap409a.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cheap 409A\naid: cheap409a-com\nurl: https://cheap409a.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not tax, legal or valuation advice\n  text: Nothing on it is tax, legal or valuation advice, and it is not a substitute for an independent appraisal\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cheap409a-com/eligibility/cheap409a-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Cheap 409A's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Valuation
- Startups
- Finance
- Pricing
---
