---
api_specs:
- filename: choozle-authorization-api-openapi.yml
  format: yaml
  label: Choozle Authorization API
  slug: choozle-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/choozle/openapi/choozle-authorization-api-openapi.yml
- filename: choozle-reporting-api-openapi.yml
  format: yaml
  label: Choozle Reporting API
  slug: choozle-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/choozle/openapi/choozle-reporting-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Smart Tag Container is controlled by U.S. Export Regulations, and may not be exported to or used by embargoed countries or individuals.
  entity_types:
  - text: You may only use the Services for your internal business purposes.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Political advertising in Washington
    text: 'Choozle does not support political advertising in the following states: Washington.'
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
name: Choozle
provenance_date: '2026-11-09'
provider_name: Choozle
provider_slug: choozle
slug: choozle-eligibility
source_date: '2026-11-09'
source_filename: choozle-eligibility.yml
source_heading: Eligibility
source_page: https://choozle.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Choozle\naid: choozle\nurl: https://choozle.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Smart Tag Container is controlled by U.S. Export Regulations, and may not be exported to or used by\n    embargoed countries or individuals.\nentity_types:\n- type: business\n  text: You may only use the Services for your internal business purposes.\nrestricted_uses:\n- summary: Political advertising in Washington\n  text: 'Choozle does not support political advertising in the following states: Washington.'\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/choozle/eligibility/choozle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Choozle's own page on 2026-11-09.
synthetic: false
tags:
- Digital Advertising
- Programmatic Advertising
- DSP
- Advertising Reporting
- Campaign Reporting
- Display Advertising
- Connected TV
- CTV
- Video Advertising
- Native Advertising
- Digital Out Of Home
- Reporting
- Real-Time Bidding
- RTB
- AdTech
---
