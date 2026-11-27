---
api_specs:
- filename: compabase-companies-api-openapi.yml
  format: yaml
  label: Compabase Companies API
  slug: compabase-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-companies-api-openapi.yml
- filename: compabase-health-api-openapi.yml
  format: yaml
  label: Compabase Health API
  slug: compabase-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-health-api-openapi.yml
- filename: compabase-persons-api-openapi.yml
  format: yaml
  label: Compabase Persons API
  slug: compabase-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-persons-api-openapi.yml
- filename: compabase-usage-api-openapi.yml
  format: yaml
  label: Compabase Usage API
  slug: compabase-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-usage-api-openapi.yml
- filename: compabase-watchlist-api-openapi.yml
  format: yaml
  label: Compabase Watchlist API
  slug: compabase-watchlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-watchlist-api-openapi.yml
- filename: compabase-financials-api-openapi.yml
  format: yaml
  label: Compabase Financials API
  slug: compabase-financials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-financials-api-openapi.yml
- filename: compabase-news-api-openapi.yml
  format: yaml
  label: Compabase News API
  slug: compabase-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-news-api-openapi.yml
- filename: compabase-registers-api-openapi.yml
  format: yaml
  label: Compabase Registers API
  slug: compabase-registers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-registers-api-openapi.yml
- filename: compabase-tenders-api-openapi.yml
  format: yaml
  label: Compabase Tenders API
  slug: compabase-tenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/compabase/openapi/compabase-tenders-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A legal person, organizational unit, or natural person acting in the course of business activity, purchasing data for professional or commercial purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Marketing and outreach restrictions
    text: 'The User shall not: use exported data for unsolicited mass marketing communications;'
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
name: Compabase
provenance_date: '2026-11-09'
provider_name: Compabase
provider_slug: compabase
slug: compabase-eligibility
source_date: '2026-11-09'
source_filename: compabase-eligibility.yml
source_heading: Eligibility
source_page: https://compabase.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Compabase\naid: compabase\nurl: https://compabase.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: A legal person, organizational unit, or natural person acting in the course of business activity, purchasing\n    data for professional or commercial purposes.\nrestricted_uses:\n- summary: Marketing and outreach restrictions\n  text: 'The User shall not: use exported data for unsolicited mass marketing communications;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/compabase/eligibility/compabase-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Compabase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Polish
- Business
- Finance
- Risk Management
- Artificial Intelligence
---
