---
api_specs:
- filename: wyndpath-com-account-api-openapi.yml
  format: yaml
  label: wyndpath-com Account API
  slug: wyndpath-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-account-api-openapi.yml
- filename: wyndpath-com-charge-api-openapi.yml
  format: yaml
  label: wyndpath-com Charge API
  slug: wyndpath-com-charge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-charge-api-openapi.yml
- filename: wyndpath-com-estimate-api-openapi.yml
  format: yaml
  label: wyndpath-com Estimate API
  slug: wyndpath-com-estimate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-estimate-api-openapi.yml
- filename: wyndpath-com-geo-api-openapi.yml
  format: yaml
  label: wyndpath-com Geo API
  slug: wyndpath-com-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-geo-api-openapi.yml
- filename: wyndpath-com-healthz-api-openapi.yml
  format: yaml
  label: wyndpath-com Healthz API
  slug: wyndpath-com-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-healthz-api-openapi.yml
- filename: wyndpath-com-internal-api-openapi.yml
  format: yaml
  label: wyndpath-com Internal API
  slug: wyndpath-com-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-internal-api-openapi.yml
- filename: wyndpath-com-profiles-api-openapi.yml
  format: yaml
  label: wyndpath-com Profiles API
  slug: wyndpath-com-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-profiles-api-openapi.yml
- filename: wyndpath-com-requests-api-openapi.yml
  format: yaml
  label: wyndpath-com Requests API
  slug: wyndpath-com-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-requests-api-openapi.yml
- filename: wyndpath-com-stats-api-openapi.yml
  format: yaml
  label: wyndpath-com Stats API
  slug: wyndpath-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-stats-api-openapi.yml
- filename: wyndpath-com-target-api-openapi.yml
  format: yaml
  label: wyndpath-com Target API
  slug: wyndpath-com-target-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-target-api-openapi.yml
- filename: wyndpath-com-wyndpath-api-openapi.yml
  format: yaml
  label: wyndpath-com Wynd Path API
  slug: wyndpath-com-wyndpath-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wyndpath-com/openapi/wyndpath-com-wyndpath-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prospecting or profiling files
    text: build prospecting or profiling files in breach of the applicable regulations
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Access requires creating an account with a valid email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: wyndpath-com
provenance_date: '2026-11-10'
provider_name: wyndpath-com
provider_slug: wyndpath-com
slug: wyndpath-com-eligibility
source_date: '2026-11-10'
source_filename: wyndpath-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.wyndpath.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: wyndpath-com\naid: wyndpath-com\nurl: https://www.wyndpath.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prospecting or profiling files\n  text: build prospecting or profiling files in breach of the applicable regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Access requires creating an account with a valid email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/wyndpath-com/eligibility/wyndpath-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from wyndpath-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data
- Automation
- Web
---
