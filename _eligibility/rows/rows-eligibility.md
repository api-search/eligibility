---
api_specs:
- filename: rows-data-api-openapi.yml
  format: yaml
  label: Rows Data API
  slug: rows-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-data-api-openapi.yml
- filename: rows-folders-api-openapi.yml
  format: yaml
  label: Rows Folders API
  slug: rows-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-folders-api-openapi.yml
- filename: rows-spreadsheets-api-openapi.yml
  format: yaml
  label: Rows Spreadsheets API
  slug: rows-spreadsheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-spreadsheets-api-openapi.yml
- filename: rows-vision-api-openapi.yml
  format: yaml
  label: Rows Vision API
  slug: rows-vision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-vision-api-openapi.yml
- filename: rows-workspaces-api-openapi.yml
  format: yaml
  label: Rows Workspaces API
  slug: rows-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rows/openapi/rows-workspaces-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The services offered on rows.com can be accessed and used solely by entrepreneurs or businesses
    type: business
  minimum_age:
    text: You must be at least 18 years of age or older to use and register for our services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: You agree not to use the services including in particular integrated third-party services and the software for any unlawful or illegal activity.
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
name: Rows
provenance_date: '2026-11-10'
provider_name: Rows
provider_slug: rows
slug: rows-eligibility
source_date: '2026-11-10'
source_filename: rows-eligibility.yml
source_heading: Eligibility
source_page: https://rows.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rows\naid: rows\nurl: https://rows.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The services offered on rows.com can be accessed and used solely by entrepreneurs or businesses\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: You agree not to use the services including in particular integrated third-party services and the software\n    for any unlawful or illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be\
  \ at least 18 years of age or older to use and register for our services.\n"
source_yaml_url: https://artifacts.apis.io/rows/eligibility/rows-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rows's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Productivity
- Spreadsheets
- Data
- No-Code
- Automation
- Artificial Intelligence
- Analytics
- Business Intelligence
---
