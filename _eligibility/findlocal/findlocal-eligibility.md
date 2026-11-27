---
api_specs:
- filename: findlocal-events-api-openapi.yml
  format: yaml
  label: FindLocal Events API
  slug: findlocal-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findlocal/openapi/findlocal-events-api-openapi.yml
- filename: findlocal-venues-api-openapi.yml
  format: yaml
  label: FindLocal Venues API
  slug: findlocal-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/findlocal/openapi/findlocal-venues-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A developer account is needed to hold API keys; to open one you must be at least 18 and able to form a binding contract.
    type: individual
  minimum_age:
    text: to open one you must be at least 18 and able to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Misrepresentation of data source
    text: Misrepresent Find Local, or present our data as your own or as an official venue listing.
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
name: FindLocal
provenance_date: '2026-11-09'
provider_name: FindLocal
provider_slug: findlocal
slug: findlocal-eligibility
source_date: '2026-11-09'
source_filename: findlocal-eligibility.yml
source_heading: Eligibility
source_page: https://findlocal.community/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FindLocal\naid: findlocal\nurl: https://findlocal.community/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A developer account is needed to hold API keys; to open one you must be at least 18 and able to form a binding\n    contract.\nrestricted_uses:\n- summary: Misrepresentation of data source\n  text: Misrepresent Find Local, or present our data as your own or as an official venue listing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: to open one you\
  \ must be at least 18 and able to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/findlocal/eligibility/findlocal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from FindLocal's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Hyperlocal
- Community
- Data
- Open Data
---
