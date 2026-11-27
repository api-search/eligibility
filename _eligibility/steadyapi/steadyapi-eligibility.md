---
api_specs:
- filename: steadyapi-collection.json
  format: json
  label: SteadyAPI
  slug: steadyapi
  spec_type: Postman
  url: https://artifacts.apis.io/steadyapi/postman/steadyapi-collection.json
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Service, you confirm that you are of legal age to enter into a binding contract in your jurisdiction.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to this Agreement.
    type: business
  minimum_age:
    text: you are of legal age to enter into a binding contract in your jurisdiction
    value: legal age
  restricted_uses:
  - summary: Illegal or unauthorized purpose
    text: Use the Service for any illegal or unauthorized purpose.
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
name: SteadyAPI
provenance_date: '2026-11-10'
provider_name: SteadyAPI
provider_slug: steadyapi
slug: steadyapi-eligibility
source_date: '2026-11-10'
source_filename: steadyapi-eligibility.yml
source_heading: Eligibility
source_page: https://steadyapi.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SteadyAPI\naid: steadyapi\nurl: https://steadyapi.com/pages/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Service, you confirm that you are of legal age to enter into a binding contract in your jurisdiction.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to this Agreement.\nrestricted_uses:\n- summary: Illegal or unauthorized purpose\n  text: Use the Service for any illegal\
  \ or unauthorized purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you are of legal age to enter into a binding contract in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/steadyapi/eligibility/steadyapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SteadyAPI's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Finance
- Stock Market
- Social Media
- Reddit
- Data as a Service
- Web Data
- Alternative Data
---
