---
api_specs:
- filename: centrica-oauth2-api-openapi.yml
  format: yaml
  label: Centrica Oauth2 API
  slug: centrica-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/centrica/openapi/centrica-oauth2-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: The products and services described on this website and app are only available in the UK.
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
name: Centrica
provenance_date: '2026-11-09'
provider_name: Centrica
provider_slug: centrica
slug: centrica-eligibility
source_date: '2026-11-09'
source_filename: centrica-eligibility.yml
source_heading: Eligibility
source_page: https://www.britishgas.co.uk/legal-compliance/terms-and-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Centrica\naid: centrica\nurl: https://www.britishgas.co.uk/legal-compliance/terms-and-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: The products and services described on this website and app are only available in the UK.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/centrica/eligibility/centrica-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Centrica's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Gas
- Smart Metering
- Energy Retail
- Energy Markets
- Ireland
- Field Service Management
---
