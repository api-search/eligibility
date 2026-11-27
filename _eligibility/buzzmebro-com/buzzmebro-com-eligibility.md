---
api_specs:
- filename: buzzmebro-com-applications-api-openapi.yml
  format: yaml
  label: BuzzMeBro Applications API
  slug: buzzmebro-com-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-applications-api-openapi.yml
- filename: buzzmebro-com-check-api-openapi.yml
  format: yaml
  label: BuzzMeBro Check API
  slug: buzzmebro-com-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-check-api-openapi.yml
- filename: buzzmebro-com-info-api-openapi.yml
  format: yaml
  label: BuzzMeBro Info API
  slug: buzzmebro-com-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-info-api-openapi.yml
- filename: buzzmebro-com-me-api-openapi.yml
  format: yaml
  label: BuzzMeBro Me API
  slug: buzzmebro-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-me-api-openapi.yml
- filename: buzzmebro-com-setups-api-openapi.yml
  format: yaml
  label: BuzzMeBro Setups API
  slug: buzzmebro-com-setups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buzzmebro-com/openapi/buzzmebro-com-setups-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: BuzzMeBro is a registered business in Canada, operating from Toronto, Ontario.
  entity_types:
  - text: You must be at least 18 and must live at, or be authorised by the resident of, the apartment you are setting up.
    type: individual
  minimum_age:
    text: You must be at least 18 and must live at, or be authorised by the resident of, the apartment you are setting up.
    value: '18'
  restricted_uses:
  - summary: Emergency calls
    text: Never use it to contact police, fire or ambulance.
  - summary: Unlawful use
    text: use it for any unlawful purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We verify every phone number by sending a one-time code to it.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BuzzMeBro
provenance_date: '2026-11-09'
provider_name: BuzzMeBro
provider_slug: buzzmebro-com
slug: buzzmebro-com-eligibility
source_date: '2026-11-09'
source_filename: buzzmebro-com-eligibility.yml
source_heading: Eligibility
source_page: https://buzzmebro.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuzzMeBro\naid: buzzmebro-com\nurl: https://buzzmebro.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: BuzzMeBro is a registered business in Canada, operating from Toronto, Ontario.\nentity_types:\n- type: individual\n  text: You must be at least 18 and must live at, or be authorised by the resident of, the apartment you are setting\n    up.\nrestricted_uses:\n- summary: Emergency calls\n  text: Never use it to contact police, fire or ambulance.\n- summary: Unlawful use\n  text: use it for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: We verify every phone number by sending a one-time code to it.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and must live at, or be authorised by the resident of, the apartment you are setting\n    up.\n"
source_yaml_url: https://artifacts.apis.io/buzzmebro-com/eligibility/buzzmebro-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BuzzMeBro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Buzzer
- Apartments
- Access
- Subscription
- Toronto
---
