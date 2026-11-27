---
api_specs:
- filename: cooperators-event-insurance-api-openapi.yml
  format: yaml
  label: The Co-operators Event Insurance API
  slug: cooperators-event-insurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cooperators/openapi/cooperators-event-insurance-api-openapi.yml
- filename: cooperators-tenant-insurance-api-openapi.yml
  format: yaml
  label: The Co-operators Tenant Insurance API
  slug: cooperators-tenant-insurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cooperators/openapi/cooperators-tenant-insurance-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: The Premium is firm and in Canadian dollars.
  entity_types:
  - text: “you” refers to you, the individual that agrees to these TOU.
    type: individual
  - source: https://www.cooperators.ca/en/security-privacy/legal
    text: The contents of the Applications and the information and data provided by the Applications are intended for private, non-commercial use by individuals only
    type: individual
  minimum_age:
    text: You (and any third-party Insured(s) if applicable) are at least sixteen (1 6 ) years of age
    value: sixteen
  restricted_uses:
  - summary: Scraping or automated harvesting
    text: harvest or scrape any content from the Platform
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
name: The Co-operators
provenance_date: '2026-11-09'
provider_name: The Co-operators
provider_slug: cooperators
slug: cooperators-eligibility
source_date: '2026-11-09'
source_filename: cooperators-eligibility.yml
source_heading: Eligibility
source_page: https://duuo.ca/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Co-operators\naid: cooperators\nurl: https://duuo.ca/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://duuo.ca/terms-of-use/\n  - https://www.cooperators.ca/en/security-privacy/legal\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: The Premium is firm and in Canadian dollars.\nentity_types:\n- type: individual\n  text: “you” refers to you, the individual that agrees to these TOU.\n- type: individual\n  text: The contents of the Applications and the information and data provided by the Applications are intended\n    for private, non-commercial use by individuals only\n  source: https://www.cooperators.ca/en/security-privacy/legal\n\
  restricted_uses:\n- summary: Scraping or automated harvesting\n  text: harvest or scrape any content from the Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: sixteen\n  text: You (and any third-party Insured(s) if applicable) are at least sixteen (1 6 ) years of age\n"
source_yaml_url: https://artifacts.apis.io/cooperators/eligibility/cooperators-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from The Co-operators's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Canada
- Property and Casualty
- Life Insurance
- Group Benefits
- Embedded Insurance
- Cooperative
- Wealth Management
- Partner API
---
