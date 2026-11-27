---
api_specs:
- filename: intelligems-create-custom-event-api-openapi.yml
  format: yaml
  label: Intelligems Create Custom Event API
  slug: intelligems-create-custom-event-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-create-custom-event-api-openapi.yml
- filename: intelligems-create-experience-api-openapi.yml
  format: yaml
  label: Intelligems Create Experience API
  slug: intelligems-create-experience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-create-experience-api-openapi.yml
- filename: intelligems-fetch-experience-data-api-openapi.yml
  format: yaml
  label: Intelligems Fetch Experience Data API
  slug: intelligems-fetch-experience-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-fetch-experience-data-api-openapi.yml
- filename: intelligems-fetch-experience-list-api-openapi.yml
  format: yaml
  label: Intelligems Fetch Experience List API
  slug: intelligems-fetch-experience-list-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-fetch-experience-list-api-openapi.yml
- filename: intelligems-fetch-sitewide-analytics-api-openapi.yml
  format: yaml
  label: Intelligems Fetch Sitewide Analytics API
  slug: intelligems-fetch-sitewide-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-fetch-sitewide-analytics-api-openapi.yml
- filename: intelligems-get-experience-export-api-openapi.yml
  format: yaml
  label: Intelligems Get Experience Export API
  slug: intelligems-get-experience-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-get-experience-export-api-openapi.yml
- filename: intelligems-get-holiday-benchmark-data-api-openapi.yml
  format: yaml
  label: Intelligems Get Holiday Benchmark Data API
  slug: intelligems-get-holiday-benchmark-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-get-holiday-benchmark-data-api-openapi.yml
- filename: intelligems-perform-experience-action-api-openapi.yml
  format: yaml
  label: Intelligems Perform Experience Action API
  slug: intelligems-perform-experience-action-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-perform-experience-action-api-openapi.yml
- filename: intelligems-update-experience-api-openapi.yml
  format: yaml
  label: Intelligems Update Experience API
  slug: intelligems-update-experience-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intelligems/openapi/intelligems-update-experience-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT
    type: business
  minimum_age:
    text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: solely for your own personal, noncommercial use
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
name: Intelligems
provenance_date: '2026-11-09'
provider_name: Intelligems
provider_slug: intelligems
slug: intelligems-eligibility
source_date: '2026-11-09'
source_filename: intelligems-eligibility.yml
source_heading: Eligibility
source_page: https://www.intelligems.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Intelligems\naid: intelligems\nurl: https://www.intelligems.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: ON BEHALF OF YOURSELF OR THE ENTITY THAT YOU REPRESENT\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: solely for your own personal, noncommercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MAY NOT ACCESS OR USE THE SITE OR ACCEPT THE TERMS IF YOU ARE NOT AT LEAST 18 YEARS OLD.\n"
source_yaml_url: https://artifacts.apis.io/intelligems/eligibility/intelligems-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Intelligems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- A/B Testing
- E-Commerce
- Pricing
- Personalization
- Conversion Rate Optimization
- Shopify
- Analytics
- Experimentation
- MCP
- Webhook
- Profit Optimization
---
