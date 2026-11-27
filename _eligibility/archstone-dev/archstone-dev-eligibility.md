---
api_specs:
- filename: archstone-dev-capabilities-api-openapi.yml
  format: yaml
  label: Archstone Capabilities API
  slug: archstone-dev-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archstone-dev/openapi/archstone-dev-capabilities-api-openapi.yml
- filename: archstone-dev-listings-api-openapi.yml
  format: yaml
  label: Archstone Listings API
  slug: archstone-dev-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archstone-dev/openapi/archstone-dev-listings-api-openapi.yml
- filename: archstone-dev-pricing-api-openapi.yml
  format: yaml
  label: Archstone Pricing API
  slug: archstone-dev-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archstone-dev/openapi/archstone-dev-pricing-api-openapi.yml
- filename: archstone-dev-verify-openapi-api-openapi.yml
  format: yaml
  label: Archstone Verify Openapi API
  slug: archstone-dev-verify-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archstone-dev/openapi/archstone-dev-verify-openapi-api-openapi.yml
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
  - summary: no special-category data in pilot
    text: during the pilot the customer must not send special categories of personal data (Art. 9) or data relating to criminal convictions and offences (Art. 10) through a hosted endpoint, unless separately agreed in writing
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Email verification gates issuance, not sign-in.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Archstone
provenance_date: '2026-11-09'
provider_name: Archstone
provider_slug: archstone-dev
slug: archstone-dev-eligibility
source_date: '2026-11-09'
source_filename: archstone-dev-eligibility.yml
source_heading: Eligibility
source_page: https://console.archstone.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Archstone\naid: archstone-dev\nurl: https://console.archstone.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: no special-category data in pilot\n  text: during the pilot the customer must not send special categories of personal data (Art. 9) or data relating\n    to criminal convictions and offences (Art. 10) through a hosted endpoint, unless separately agreed in writing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Email verification gates issuance, not sign-in.\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/archstone-dev/eligibility/archstone-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Archstone's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Connector
- No-Code
- Pricing
- Business
---
