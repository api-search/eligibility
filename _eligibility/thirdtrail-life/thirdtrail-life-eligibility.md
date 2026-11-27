---
api_specs:
- filename: thirdtrail-life-ephemerides-api-openapi.yml
  format: yaml
  label: thirdtrail-life Ephemerides API
  slug: thirdtrail-life-ephemerides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-ephemerides-api-openapi.yml
- filename: thirdtrail-life-mcp-api-openapi.yml
  format: yaml
  label: thirdtrail-life MCP API
  slug: thirdtrail-life-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-mcp-api-openapi.yml
- filename: thirdtrail-life-solar-api-openapi.yml
  format: yaml
  label: thirdtrail-life Solar API
  slug: thirdtrail-life-solar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-solar-api-openapi.yml
- filename: thirdtrail-life-tides-api-openapi.yml
  format: yaml
  label: thirdtrail-life Tides API
  slug: thirdtrail-life-tides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-tides-api-openapi.yml
- filename: thirdtrail-life-utility-api-openapi.yml
  format: yaml
  label: thirdtrail-life Utility API
  slug: thirdtrail-life-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thirdtrail-life/openapi/thirdtrail-life-utility-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age, or the age of majority in your jurisdiction if it is higher.
    type: individual
  - text: If you are acting on behalf of an organisation, you warrant that you are authorised to bind that organisation to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years of age, or the age of majority in your jurisdiction if it is higher.
    value: '18'
  restricted_uses:
  - summary: No safety-critical or navigational use
    text: No safety-critical or navigational use.
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
name: thirdtrail-life
provenance_date: '2026-11-10'
provider_name: thirdtrail-life
provider_slug: thirdtrail-life
slug: thirdtrail-life-eligibility
source_date: '2026-11-10'
source_filename: thirdtrail-life-eligibility.yml
source_heading: Eligibility
source_page: https://thirdtrail.life/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: thirdtrail-life\naid: thirdtrail-life\nurl: https://thirdtrail.life/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age, or the age of majority in your jurisdiction if it is higher.\n- type: business\n  text: If you are acting on behalf of an organisation, you warrant that you are authorised to bind that organisation\n    to these Terms.\nrestricted_uses:\n- summary: No safety-critical or navigational use\n  text: No safety-critical or navigational use.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age, or the age of majority in your jurisdiction if it is higher.\n"
source_yaml_url: https://artifacts.apis.io/thirdtrail-life/eligibility/thirdtrail-life-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from thirdtrail-life's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Astronomy
- Tides
- Solar
---
