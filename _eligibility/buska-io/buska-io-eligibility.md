---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Client" : any legal entity or professional acting in a business capacity that subscribes to or uses the Service.'
    type: business
  - text: '"User" : any natural person who accesses or uses the Service on behalf of a Client.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional/business use only
    text: The Service is intended for professional and business use only.
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
name: Buska
provenance_date: '2026-11-09'
provider_name: Buska
provider_slug: buska-io
slug: buska-io-eligibility
source_date: '2026-11-09'
source_filename: buska-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.buska.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buska\naid: buska-io\nurl: https://www.buska.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"Client\" : any legal entity or professional acting in a business capacity that subscribes to or uses the\n    Service.'\n- type: individual\n  text: '\"User\" : any natural person who accesses or uses the Service on behalf of a Client.'\nrestricted_uses:\n- summary: Professional/business use only\n  text: The Service is intended for professional and business use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/buska-io/eligibility/buska-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Buska's own page on 2026-11-09.
synthetic: false
tags:
- Social Listening
- Lead Generation
- Artificial Intelligence
- B2B
- Marketing
---
