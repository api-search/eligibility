---
api_specs:
- filename: listbulb-openapi-generated.yml
  format: yaml
  label: List Bulb API
  slug: listbulb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/listbulb/openapi/_ae-authored/listbulb-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be able to form a binding contract and use the Service only as permitted by law.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No adult or sexually explicit listings
    text: Listings and linked websites must not contain pornography, sexually explicit material, adult entertainment, sexual services, exploitation, or other content we determine is inappropriate for the Service.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Review is manual and editorial. Approval is not guaranteed for any listing option, including paid options.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: List Bulb
provenance_date: '2026-11-09'
provider_name: List Bulb
provider_slug: listbulb
slug: listbulb-eligibility
source_date: '2026-11-09'
source_filename: listbulb-eligibility.yml
source_heading: Eligibility
source_page: https://listbulb.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: List Bulb\naid: listbulb\nurl: https://listbulb.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be able to form a binding contract and use the Service only as permitted by law.\nrestricted_uses:\n- summary: No adult or sexually explicit listings\n  text: Listings and linked websites must not contain pornography, sexually explicit material, adult entertainment,\n    sexual services, exploitation, or other content we determine is inappropriate for the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: Review is manual and editorial. Approval is not guaranteed for any listing option, including paid options.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/listbulb/eligibility/listbulb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from List Bulb's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Software-as-a-Service
- Directory
- Startups
---
