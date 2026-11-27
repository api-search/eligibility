---
api_specs:
- filename: alishahiinsurance-com-agent-api-openapi.yml
  format: yaml
  label: Alishahi Insurance Agent API
  slug: alishahiinsurance-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alishahiinsurance-com/openapi/alishahiinsurance-com-agent-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: licensed in all 50 states and Washington, DC
  entity_types:
  - text: send a request only for yourself, your business, or someone who has asked you to.
    type: business
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
name: Alishahi Insurance
provenance_date: '2026-11-09'
provider_name: Alishahi Insurance
provider_slug: alishahiinsurance-com
slug: alishahiinsurance-com-eligibility
source_date: '2026-11-09'
source_filename: alishahiinsurance-com-eligibility.yml
source_heading: Eligibility
source_page: https://alishahiinsurance.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alishahi Insurance\naid: alishahiinsurance-com\nurl: https://alishahiinsurance.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: licensed in all 50 states and Washington, DC\nentity_types:\n- type: business\n  text: send a request only for yourself, your business, or someone who has asked you to.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alishahiinsurance-com/eligibility/alishahiinsurance-com-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Alishahi Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Brokerage
- Beverly Hills
- California
- United States
---
