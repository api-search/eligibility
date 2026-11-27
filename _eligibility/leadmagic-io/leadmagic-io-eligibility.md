---
api_specs:
- filename: leadmagic-io-ads-data-api-openapi.yml
  format: yaml
  label: leadmagic-io Ads Data API
  slug: leadmagic-io-ads-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-ads-data-api-openapi.yml
- filename: leadmagic-io-analytics-api-openapi.yml
  format: yaml
  label: leadmagic-io Analytics API
  slug: leadmagic-io-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-analytics-api-openapi.yml
- filename: leadmagic-io-batch-api-openapi.yml
  format: yaml
  label: leadmagic-io Batch API
  slug: leadmagic-io-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-batch-api-openapi.yml
- filename: leadmagic-io-bulk-jobs-api-openapi.yml
  format: yaml
  label: leadmagic-io Bulk Jobs API
  slug: leadmagic-io-bulk-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-bulk-jobs-api-openapi.yml
- filename: leadmagic-io-company-data-api-openapi.yml
  format: yaml
  label: leadmagic-io Company Data API
  slug: leadmagic-io-company-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-company-data-api-openapi.yml
- filename: leadmagic-io-cost-control-api-openapi.yml
  format: yaml
  label: leadmagic-io Cost Control API
  slug: leadmagic-io-cost-control-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-cost-control-api-openapi.yml
- filename: leadmagic-io-credits-api-openapi.yml
  format: yaml
  label: leadmagic-io Credits API
  slug: leadmagic-io-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-credits-api-openapi.yml
- filename: leadmagic-io-jobs-data-api-openapi.yml
  format: yaml
  label: leadmagic-io Jobs Data API
  slug: leadmagic-io-jobs-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-jobs-data-api-openapi.yml
- filename: leadmagic-io-people-enrichment-api-openapi.yml
  format: yaml
  label: leadmagic-io People Enrichment API
  slug: leadmagic-io-people-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadmagic-io/openapi/leadmagic-io-people-enrichment-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company is registered in Massachusetts, United States; no country-level service restrictions stated in the visible text.
  entity_types:
  - text: The Services are offered only to businesses and individuals acting in a business or professional capacity.
    type: business
  minimum_age:
    text: The Services are intended for users who are at least 18 years old and have the legal capacity to enter into a binding agreement.
    value: '18'
  restricted_uses:
  - summary: Consumer, FCRA and people-search uses
    text: Using the Services, data, or outputs for credit, insurance, employment, housing, lending, tenant screening, education, healthcare, criminal justice, eligibility, consumer reports, or any purpose regulated by the Fair Credit Reporting Act or similar laws
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
name: leadmagic-io
provenance_date: '2026-11-09'
provider_name: leadmagic-io
provider_slug: leadmagic-io
slug: leadmagic-io-eligibility
source_date: '2026-11-09'
source_filename: leadmagic-io-eligibility.yml
source_heading: Eligibility
source_page: https://leadmagic.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: leadmagic-io\naid: leadmagic-io\nurl: https://leadmagic.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Company is registered in Massachusetts, United States; no country-level service restrictions stated in the\n    visible text.\nentity_types:\n- type: business\n  text: The Services are offered only to businesses and individuals acting in a business or professional capacity.\nrestricted_uses:\n- summary: Consumer, FCRA and people-search uses\n  text: Using the Services, data, or outputs for credit, insurance, employment, housing, lending, tenant\
  \ screening,\n    education, healthcare, criminal justice, eligibility, consumer reports, or any purpose regulated by the Fair\n    Credit Reporting Act or similar laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old and have the legal capacity to enter into\n    a binding agreement.\n"
source_yaml_url: https://artifacts.apis.io/leadmagic-io/eligibility/leadmagic-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from leadmagic-io's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Data Enrichment
- Lead Generation
- Email Verification
- Company Intelligence
---
