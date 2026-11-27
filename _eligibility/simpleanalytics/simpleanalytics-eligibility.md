---
api_specs:
- filename: simpleanalytics-events-api-openapi.yml
  format: yaml
  label: Simple Analytics Events API
  slug: simpleanalytics-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-events-api-openapi.yml
- filename: simpleanalytics-export-api-openapi.yml
  format: yaml
  label: Simple Analytics Export API
  slug: simpleanalytics-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-export-api-openapi.yml
- filename: simpleanalytics-stats-api-openapi.yml
  format: yaml
  label: Simple Analytics Stats API
  slug: simpleanalytics-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-stats-api-openapi.yml
- filename: simpleanalytics-websites-api-openapi.yml
  format: yaml
  label: Simple Analytics Websites API
  slug: simpleanalytics-websites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/simpleanalytics/openapi/simpleanalytics-websites-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If client has not yet reached the age of 18 years, consent of parents or guardians is required before purchasing a plan.
    value: '18'
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
name: Simple Analytics
provenance_date: '2026-11-10'
provider_name: Simple Analytics
provider_slug: simpleanalytics
slug: simpleanalytics-eligibility
source_date: '2026-11-10'
source_filename: simpleanalytics-eligibility.yml
source_heading: Eligibility
source_page: https://www.simpleanalytics.com/general-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Simple Analytics\naid: simpleanalytics\nurl: https://www.simpleanalytics.com/general-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If client has not yet reached the age of 18 years, consent of parents or guardians is required before purchasing\n    a plan.\n"
source_yaml_url: https://artifacts.apis.io/simpleanalytics/eligibility/simpleanalytics-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Simple Analytics's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Web Analytics
- Privacy
- Cookieless
- GDPR
- Event
- Data Export
- Europe
---
