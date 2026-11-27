---
api_specs:
- filename: dealogic-admin-api-openapi.yml
  format: yaml
  label: Dealogic Admin API
  slug: dealogic-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-admin-api-openapi.yml
- filename: dealogic-data-api-openapi.yml
  format: yaml
  label: Dealogic Data API
  slug: dealogic-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-data-api-openapi.yml
- filename: dealogic-dcmdeal-api-openapi.yml
  format: yaml
  label: Dealogic Dcm Deal API
  slug: dealogic-dcmdeal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-dcmdeal-api-openapi.yml
- filename: dealogic-entity-navigation-api-openapi.yml
  format: yaml
  label: Dealogic Entity Navigation API
  slug: dealogic-entity-navigation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-entity-navigation-api-openapi.yml
- filename: dealogic-levfinmarketupdate-api-openapi.yml
  format: yaml
  label: Dealogic Levfin Market Update API
  slug: dealogic-levfinmarketupdate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-levfinmarketupdate-api-openapi.yml
- filename: dealogic-loandeal-api-openapi.yml
  format: yaml
  label: Dealogic Loan Deal API
  slug: dealogic-loandeal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-loandeal-api-openapi.yml
- filename: dealogic-organizationspacprofile-api-openapi.yml
  format: yaml
  label: Dealogic Organization Spac Profile API
  slug: dealogic-organizationspacprofile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-organizationspacprofile-api-openapi.yml
- filename: dealogic-related-entities-api-openapi.yml
  format: yaml
  label: Dealogic Related Entities API
  slug: dealogic-related-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-related-entities-api-openapi.yml
- filename: dealogic-reportdata-api-openapi.yml
  format: yaml
  label: Dealogic Report Data API
  slug: dealogic-reportdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-reportdata-api-openapi.yml
- filename: dealogic-root-entity-api-openapi.yml
  format: yaml
  label: Dealogic Root Entity API
  slug: dealogic-root-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-root-entity-api-openapi.yml
- filename: dealogic-spac-admin-api-openapi.yml
  format: yaml
  label: Dealogic Spac Admin API
  slug: dealogic-spac-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-spac-admin-api-openapi.yml
- filename: dealogic-spac-reader-api-openapi.yml
  format: yaml
  label: Dealogic Spac Reader API
  slug: dealogic-spac-reader-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-spac-reader-api-openapi.yml
- filename: dealogic-spac-writer-api-openapi.yml
  format: yaml
  label: Dealogic Spac Writer API
  slug: dealogic-spac-writer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-spac-writer-api-openapi.yml
- filename: dealogic-test-api-openapi.yml
  format: yaml
  label: Dealogic Test API
  slug: dealogic-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealogic/openapi/dealogic-test-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our site is directed to people residing in the United Kingdom.
  entity_types:
  - text: If you are a business, these terms of use, its subject matter and its formation (and any non-contractual disputes or claims) are governed by English law.
    type: business
  - text: If you are a consumer, please note that these terms of use, its subject matter and its formation, are governed by English law.
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Dealogic
provenance_date: '2026-11-09'
provider_name: Dealogic
provider_slug: dealogic
slug: dealogic-eligibility
source_date: '2026-11-09'
source_filename: dealogic-eligibility.yml
source_heading: Eligibility
source_page: https://dealogic.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dealogic\naid: dealogic\nurl: https://dealogic.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our site is directed to people residing in the United Kingdom.\nentity_types:\n- type: business\n  text: If you are a business, these terms of use, its subject matter and its formation (and any non-contractual\n    disputes or claims) are governed by English law.\n- type: individual\n  text: If you are a consumer, please note that these terms of use, its subject matter and its formation, are governed\n    by English law.\nrestricted_uses: []\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dealogic/eligibility/dealogic-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 3 quoted statements, read from Dealogic's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Capital Markets
- Compliance
- Deal Management
- Debt Capital Markets
- Equity Capital Markets
- Finance
- Financial Data
- Investment Banking
- League Tables
- M&A
- OData
- Private Equity
- Reporting
- SPAC
- Syndicated Loans
---
