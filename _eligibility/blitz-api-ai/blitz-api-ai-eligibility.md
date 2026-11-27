---
api_specs:
- filename: blitz-api-ai-account-api-openapi.yml
  format: yaml
  label: blitz-api-ai Account API
  slug: blitz-api-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-account-api-openapi.yml
- filename: blitz-api-ai-changelog-api-openapi.yml
  format: yaml
  label: blitz-api-ai Changelog API
  slug: blitz-api-ai-changelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-changelog-api-openapi.yml
- filename: blitz-api-ai-company-api-openapi.yml
  format: yaml
  label: blitz-api-ai Company API
  slug: blitz-api-ai-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-company-api-openapi.yml
- filename: blitz-api-ai-company-enrichment-api-openapi.yml
  format: yaml
  label: blitz-api-ai Company Enrichment API
  slug: blitz-api-ai-company-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-company-enrichment-api-openapi.yml
- filename: blitz-api-ai-company-search-api-openapi.yml
  format: yaml
  label: blitz-api-ai Company Search API
  slug: blitz-api-ai-company-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-company-search-api-openapi.yml
- filename: blitz-api-ai-enrichment-api-openapi.yml
  format: yaml
  label: blitz-api-ai Enrichment API
  slug: blitz-api-ai-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-enrichment-api-openapi.yml
- filename: blitz-api-ai-job-search-api-openapi.yml
  format: yaml
  label: blitz-api-ai Job Search API
  slug: blitz-api-ai-job-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-job-search-api-openapi.yml
- filename: blitz-api-ai-jobs-api-openapi.yml
  format: yaml
  label: blitz-api-ai Jobs API
  slug: blitz-api-ai-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-jobs-api-openapi.yml
- filename: blitz-api-ai-people-enrichment-api-openapi.yml
  format: yaml
  label: blitz-api-ai People Enrichment API
  slug: blitz-api-ai-people-enrichment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-people-enrichment-api-openapi.yml
- filename: blitz-api-ai-people-search-api-openapi.yml
  format: yaml
  label: blitz-api-ai People Search API
  slug: blitz-api-ai-people-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-people-search-api-openapi.yml
- filename: blitz-api-ai-search-api-openapi.yml
  format: yaml
  label: blitz-api-ai Search API
  slug: blitz-api-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-search-api-openapi.yml
- filename: blitz-api-ai-utilities-api-openapi.yml
  format: yaml
  label: blitz-api-ai Utilities API
  slug: blitz-api-ai-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-utilities-api-openapi.yml
- filename: blitz-api-ai-zeroclick-api-openapi.yml
  format: yaml
  label: blitz-api-ai Zeroclick API
  slug: blitz-api-ai-zeroclick-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-api-ai/openapi/blitz-api-ai-zeroclick-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Terms apply exclusively to professional B2B Clients. The Services are not available to consumers or for B2C purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competitors
    text: The Client may not access or use the Services if the Client or any of its Authorized Users is a competitor of BlitzAPI
  - summary: No sanctioned persons or territories
    text: nor for the benefit of any sanctioned person or territory.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Account creation requires a valid professional email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: blitz-api-ai
provenance_date: '2026-11-09'
provider_name: blitz-api-ai
provider_slug: blitz-api-ai
slug: blitz-api-ai-eligibility
source_date: '2026-11-09'
source_filename: blitz-api-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.blitz-api.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: blitz-api-ai\naid: blitz-api-ai\nurl: https://www.blitz-api.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Terms apply exclusively to professional B2B Clients. The Services are not available to consumers or\n    for B2C purposes.\nrestricted_uses:\n- summary: No competitors\n  text: The Client may not access or use the Services if the Client or any of its Authorized Users is a competitor\n    of BlitzAPI\n- summary: No sanctioned persons or territories\n  text: nor for the benefit of any sanctioned person or territory.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Account creation requires a valid professional email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blitz-api-ai/eligibility/blitz-api-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from blitz-api-ai's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Data
- Data Enrichment
- Go-To-Market
---
