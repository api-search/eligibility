---
api_specs:
- filename: hydro-ottawa-applicationinformation-api-openapi.yml
  format: yaml
  label: Hydro Ottawa Application Information API
  slug: hydro-ottawa-applicationinformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydro-ottawa/openapi/hydro-ottawa-applicationinformation-api-openapi.yml
- filename: hydro-ottawa-authorization-api-openapi.yml
  format: yaml
  label: Hydro Ottawa Authorization API
  slug: hydro-ottawa-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydro-ottawa/openapi/hydro-ottawa-authorization-api-openapi.yml
- filename: hydro-ottawa-batch-api-openapi.yml
  format: yaml
  label: Hydro Ottawa Batch API
  slug: hydro-ottawa-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydro-ottawa/openapi/hydro-ottawa-batch-api-openapi.yml
- filename: hydro-ottawa-usagepoint-api-openapi.yml
  format: yaml
  label: Hydro Ottawa Usage Point API
  slug: hydro-ottawa-usagepoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hydro-ottawa/openapi/hydro-ottawa-usagepoint-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Large commercial customers interested in receiving outage alerts will need to opt in via their MyAccount portal.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful messages
    text: send or otherwise make available via email and/or SMS/Text content that is unlawful, harmful, threatening, abusive, harassing, tortious, defamatory, vulgar, obscene, libellous, invasive of another’s privacy, or contains hate speech
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
name: Hydro Ottawa
provenance_date: '2026-11-09'
provider_name: Hydro Ottawa
provider_slug: hydro-ottawa
slug: hydro-ottawa-eligibility
source_date: '2026-11-09'
source_filename: hydro-ottawa-eligibility.yml
source_heading: Eligibility
source_page: https://hydroottawa.com/en/about-us/policies-and-terms/terms-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hydro Ottawa\naid: hydro-ottawa\nurl: https://hydroottawa.com/en/about-us/policies-and-terms/terms-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Large commercial customers interested in receiving outage alerts will need to opt in via their MyAccount\n    portal.\nrestricted_uses:\n- summary: Unlawful or harmful messages\n  text: send or otherwise make available via email and/or SMS/Text content that is unlawful, harmful, threatening,\n    abusive, harassing, tortious, defamatory, vulgar, obscene, libellous, invasive of another’s\
  \ privacy, or contains\n    hate speech\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hydro-ottawa/eligibility/hydro-ottawa-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Hydro Ottawa's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Canada
- Ontario
- Utilities
- Electricity
- Electricity Distribution
- Smart Metering
- Green Button
- ESPI
- Municipal Utility
- Renewables
- Hydroelectric
- Solar
- Demand Response
- Grid
---
