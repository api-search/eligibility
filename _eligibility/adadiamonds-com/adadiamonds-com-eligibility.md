---
api_specs:
- filename: adadiamonds-com-agentic-checkout-acp-api-openapi.yml
  format: yaml
  label: Ada Diamonds Agentic checkout (ACP) API
  slug: adadiamonds-com-agentic-checkout-acp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-agentic-checkout-acp-api-openapi.yml
- filename: adadiamonds-com-agentic-checkout-hosted-link-api-openapi.yml
  format: yaml
  label: Ada Diamonds Agentic checkout (hosted link) API
  slug: adadiamonds-com-agentic-checkout-hosted-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-agentic-checkout-hosted-link-api-openapi.yml
- filename: adadiamonds-com-agentic-checkout-ucp-api-openapi.yml
  format: yaml
  label: Ada Diamonds Agentic checkout (UCP) API
  slug: adadiamonds-com-agentic-checkout-ucp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-agentic-checkout-ucp-api-openapi.yml
- filename: adadiamonds-com-agentic-commerce-discovery-api-openapi.yml
  format: yaml
  label: Ada Diamonds Agentic commerce discovery API
  slug: adadiamonds-com-agentic-commerce-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-agentic-commerce-discovery-api-openapi.yml
- filename: adadiamonds-com-appointments-api-openapi.yml
  format: yaml
  label: Ada Diamonds Appointments API
  slug: adadiamonds-com-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-appointments-api-openapi.yml
- filename: adadiamonds-com-bulk-api-openapi.yml
  format: yaml
  label: Ada Diamonds Bulk API
  slug: adadiamonds-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-bulk-api-openapi.yml
- filename: adadiamonds-com-catalog-api-openapi.yml
  format: yaml
  label: Ada Diamonds Catalog API
  slug: adadiamonds-com-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-catalog-api-openapi.yml
- filename: adadiamonds-com-content-api-openapi.yml
  format: yaml
  label: Ada Diamonds Content API
  slug: adadiamonds-com-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-content-api-openapi.yml
- filename: adadiamonds-com-discovery-api-openapi.yml
  format: yaml
  label: Ada Diamonds Discovery API
  slug: adadiamonds-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-discovery-api-openapi.yml
- filename: adadiamonds-com-mcp-api-openapi.yml
  format: yaml
  label: Ada Diamonds MCP API
  slug: adadiamonds-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-mcp-api-openapi.yml
- filename: adadiamonds-com-onboarding-api-openapi.yml
  format: yaml
  label: Ada Diamonds Onboarding API
  slug: adadiamonds-com-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-onboarding-api-openapi.yml
- filename: adadiamonds-com-search-api-openapi.yml
  format: yaml
  label: Ada Diamonds Search API
  slug: adadiamonds-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adadiamonds-com/openapi/adadiamonds-com-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: APJI does not knowingly collect personal information from children under the age of thirteen (13).
    value: null
  restricted_uses:
  - summary: Refusal of service for fraud or abuse
    text: Ada Diamonds reserves the right to refuse service to anyone for any reason, including but not limited to suspected fraud or suspicious behavior
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: You may be asked to provide government-issued photo identification at the time of payment, including a copy of your passport.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ada Diamonds
provenance_date: '2026-11-09'
provider_name: Ada Diamonds
provider_slug: adadiamonds-com
slug: adadiamonds-com-eligibility
source_date: '2026-11-09'
source_filename: adadiamonds-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.adadiamonds.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ada Diamonds\naid: adadiamonds-com\nurl: https://www.adadiamonds.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Refusal of service for fraud or abuse\n  text: Ada Diamonds reserves the right to refuse service to anyone for any reason, including but not limited to\n    suspected fraud or suspicious behavior\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: You may be asked to provide government-issued photo identification at the time of payment, including a copy\n    of your\
  \ passport.\nminimum_age:\n  value: null\n  text: APJI does not knowingly collect personal information from children under the age of thirteen (13).\n"
source_yaml_url: https://artifacts.apis.io/adadiamonds-com/eligibility/adadiamonds-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Ada Diamonds's own page on 2026-11-09.
synthetic: false
tags:
- Jewelry
- Lab Diamonds
- Engagement Rings
- New York
- E-Commerce
---
