---
api_specs:
- filename: lusha-search-api-openapi.yml
  format: yaml
  label: Lusha Search API
  slug: lusha-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-search-api-openapi.yml
- filename: lusha-enrich-api-openapi.yml
  format: yaml
  label: Lusha Enrich API
  slug: lusha-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-enrich-api-openapi.yml
- filename: lusha-search-enrich-api-openapi.yml
  format: yaml
  label: Lusha Search & Enrich API
  slug: lusha-search-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-search-enrich-api-openapi.yml
- filename: lusha-prospecting-api-openapi.yml
  format: yaml
  label: Lusha Prospecting API
  slug: lusha-prospecting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-prospecting-api-openapi.yml
- filename: lusha-lookalikes-api-openapi.yml
  format: yaml
  label: Lusha Lookalikes API
  slug: lusha-lookalike-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-lookalikes-api-openapi.yml
- filename: lusha-buying-group-api-openapi.yml
  format: yaml
  label: Lusha Buying Group API
  slug: lusha-buying-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-buying-group-api-openapi.yml
- filename: lusha-signals-api-openapi.yml
  format: yaml
  label: Lusha Signals API
  slug: lusha-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-signals-api-openapi.yml
- filename: lusha-website-visits-api-openapi.yml
  format: yaml
  label: Lusha Website Visitors API
  slug: lusha-website-visits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-website-visits-api-openapi.yml
- filename: lusha-filters-api-openapi.yml
  format: yaml
  label: Lusha Filters API
  slug: lusha-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-filters-api-openapi.yml
- filename: lusha-contacts-tables-api-openapi.yml
  format: yaml
  label: Lusha Contacts Tables API
  slug: lusha-contacts-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-contacts-tables-api-openapi.yml
- filename: lusha-companies-tables-api-openapi.yml
  format: yaml
  label: Lusha Companies Tables API
  slug: lusha-companies-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-companies-tables-api-openapi.yml
- filename: lusha-webhooks-api-openapi.yml
  format: yaml
  label: Lusha Webhooks API
  slug: lusha-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-webhooks-api-openapi.yml
- filename: lusha-account-api-openapi.yml
  format: yaml
  label: Lusha Account API
  slug: lusha-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-account-api-openapi.yml
- filename: lusha-account-management-api-openapi.yml
  format: yaml
  label: Lusha Account Management API
  slug: lusha-account-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-account-management-api-openapi.yml
- filename: lusha-company-filters-api-openapi.yml
  format: yaml
  label: Lusha Company Filters API
  slug: lusha-company-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-company-filters-api-openapi.yml
- filename: lusha-contact-filters-api-openapi.yml
  format: yaml
  label: Lusha Contact Filters API
  slug: lusha-contact-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-contact-filters-api-openapi.yml
- filename: lusha-enrichment-api-openapi.yml
  format: yaml
  label: Lusha Enrichment API
  slug: lusha-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-enrichment-api-openapi.yml
- filename: lusha-prospecting-search-enrich-api-openapi.yml
  format: yaml
  label: Lusha Prospecting - Search & Enrich API
  slug: lusha-prospecting-search-enrich-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lusha/openapi/lusha-prospecting-search-enrich-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are authorized to enter this Agreement on behalf of such business organization
    type: business
  minimum_age:
    text: 'An End User must: (i) be at least 18 years of age'
    value: '18'
  restricted_uses:
  - summary: consumer credit or insurance eligibility
    text: use the Platform to determine a consumer’s eligibility for credit or insurance for personal, family, or household purposes
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
name: Lusha
provenance_date: '2026-11-10'
provider_name: Lusha
provider_slug: lusha
slug: lusha-eligibility
source_date: '2026-11-10'
source_filename: lusha-eligibility.yml
source_heading: Eligibility
source_page: https://www.lusha.com/legal/terms_and_conditions-2/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lusha\naid: lusha\nurl: https://www.lusha.com/legal/terms_and_conditions-2/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you are authorized to enter this Agreement on behalf of such business organization\nrestricted_uses:\n- summary: consumer credit or insurance eligibility\n  text: use the Platform to determine a consumer’s eligibility for credit or insurance for personal, family, or\n    household purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: 'An End User must: (i) be at least 18 years of age'\n"
source_yaml_url: https://artifacts.apis.io/lusha/eligibility/lusha-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Lusha's own page on 2026-11-10.
synthetic: false
tags:
- Sales Intelligence
- B2B
- Data Enrichment
- Contact Data
- Prospecting
- Intents
- Signals
- Lookalikes
- Webhook
- MCP
---
