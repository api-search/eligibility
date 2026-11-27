---
api_specs:
- filename: dillilabs-com-analyze-api-openapi.yml
  format: yaml
  label: Dilli Labs Analyze API
  slug: dillilabs-com-analyze-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dillilabs-com/openapi/dillilabs-com-analyze-api-openapi.yml
- filename: dillilabs-com-health-api-openapi.yml
  format: yaml
  label: Dilli Labs Health API
  slug: dillilabs-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dillilabs-com/openapi/dillilabs-com-health-api-openapi.yml
- filename: dillilabs-com-privacy-api-openapi.yml
  format: yaml
  label: Dilli Labs Privacy API
  slug: dillilabs-com-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dillilabs-com/openapi/dillilabs-com-privacy-api-openapi.yml
- filename: dillilabs-com-purchase-api-openapi.yml
  format: yaml
  label: Dilli Labs Purchase API
  slug: dillilabs-com-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dillilabs-com/openapi/dillilabs-com-purchase-api-openapi.yml
- filename: dillilabs-com-user-api-openapi.yml
  format: yaml
  label: Dilli Labs User API
  slug: dillilabs-com-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dillilabs-com/openapi/dillilabs-com-user-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is available only to individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Website is available only to individuals who are at least 13 years old.
    value: '13'
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
name: Dilli Labs
provenance_date: '2026-11-09'
provider_name: Dilli Labs
provider_slug: dillilabs-com
slug: dillilabs-com-eligibility
source_date: '2026-11-09'
source_filename: dillilabs-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.dillilabs.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dilli Labs\naid: dillilabs-com\nurl: https://www.dillilabs.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is available only to individuals who are at least 13 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is available only to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/dillilabs-com/eligibility/dillilabs-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Dilli Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- IP Geolocation
- IP Validation
- Profanity Detection
- MCP
- Software-as-a-Service
- Web Hosting
- Software Development
---
