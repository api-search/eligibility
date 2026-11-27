---
api_specs:
- filename: utilita-components-api-openapi.yml
  format: yaml
  label: Utilita Components API
  slug: utilita-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utilita/openapi/utilita-components-api-openapi.yml
- filename: utilita-incidents-api-openapi.yml
  format: yaml
  label: Utilita Incidents API
  slug: utilita-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utilita/openapi/utilita-incidents-api-openapi.yml
- filename: utilita-scheduled-maintenance-api-openapi.yml
  format: yaml
  label: Utilita Scheduled Maintenance API
  slug: utilita-scheduled-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utilita/openapi/utilita-scheduled-maintenance-api-openapi.yml
- filename: utilita-status-api-openapi.yml
  format: yaml
  label: Utilita Status API
  slug: utilita-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/utilita/openapi/utilita-status-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether you are a visitor, a client, a customer, a partner, a third-party broker or otherwise
    type: other
  minimum_age:
    text: You must be over 16 years of age to download and use our App.
    value: '16'
  restricted_uses:
  - summary: Lawful use only
    text: You agree to use the Website for lawful purposes only.
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
name: Utilita
provenance_date: '2026-11-10'
provider_name: Utilita
provider_slug: utilita
slug: utilita-eligibility
source_date: '2026-11-10'
source_filename: utilita-eligibility.yml
source_heading: Eligibility
source_page: https://utilita.co.uk/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Utilita\naid: utilita\nurl: https://utilita.co.uk/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: whether you are a visitor, a client, a customer, a partner, a third-party broker or otherwise\nrestricted_uses:\n- summary: Lawful use only\n  text: You agree to use the Website for lawful purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be over 16 years of age to download and use our App.\n"
source_yaml_url: https://artifacts.apis.io/utilita/eligibility/utilita-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Utilita's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United Kingdom
- Utilities
- Electricity
- Gas
- Smart Metering
- Prepayment
- Energy Retail
- Status
- Operational Transparency
---
