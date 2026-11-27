---
api_specs:
- filename: spade-card-enrichment-api-openapi.yml
  format: yaml
  label: Spade Card Enrichment API
  slug: spade-card-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-card-enrichment-api-openapi.yml
- filename: spade-category-action-triggers-api-openapi.yml
  format: yaml
  label: Spade Category Action Triggers API
  slug: spade-category-action-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-category-action-triggers-api-openapi.yml
- filename: spade-category-personalization-api-openapi.yml
  format: yaml
  label: Spade Category Personalization API
  slug: spade-category-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-category-personalization-api-openapi.yml
- filename: spade-feedback-and-reporting-api-openapi.yml
  format: yaml
  label: Spade Feedback and Reporting API
  slug: spade-feedback-and-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-feedback-and-reporting-api-openapi.yml
- filename: spade-merchant-action-triggers-api-openapi.yml
  format: yaml
  label: Spade Merchant Action Triggers API
  slug: spade-merchant-action-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-merchant-action-triggers-api-openapi.yml
- filename: spade-merchant-search-api-openapi.yml
  format: yaml
  label: Spade Merchant Search API
  slug: spade-merchant-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-merchant-search-api-openapi.yml
- filename: spade-transfer-enrichment-api-openapi.yml
  format: yaml
  label: Spade Transfer Enrichment API
  slug: spade-transfer-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-transfer-enrichment-api-openapi.yml
- filename: spade-universal-enrichment-api-openapi.yml
  format: yaml
  label: Spade Universal Enrichment API
  slug: spade-universal-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spade/openapi/spade-universal-enrichment-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: use the Site for any illegal purpose or in violation of any local, state, national, or international law
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
name: Spade
provenance_date: '2026-11-10'
provider_name: Spade
provider_slug: spade
slug: spade-eligibility
source_date: '2026-11-10'
source_filename: spade-eligibility.yml
source_heading: Eligibility
source_page: https://www.spade.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spade\naid: spade\nurl: https://www.spade.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority to bind you to these Terms\nrestricted_uses:\n- summary: Illegal purposes\n  text: use the Site for any illegal\
  \ purpose or in violation of any local, state, national, or international law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/spade/eligibility/spade-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Spade's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Transaction Enrichment
- Merchant Intelligence
- Payments
- Data Enrichment
- Fraud and Risk
- Fintech
- A2A
---
