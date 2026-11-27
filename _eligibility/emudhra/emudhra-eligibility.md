---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not and will not when using the Services be located in, under the control of, or a national or resident of a U.S embargoed country or territory
  entity_types:
  - text: If You are entering into this Agreement on behalf of a company, organization or another legal entity (an "Entity"), You are agreeing to this Agreement for that Entity
    type: business
  - text: You represent and warrant that you are of legal age (18 years or older or otherwise of legal age in your resident jurisdiction)
    type: individual
  minimum_age:
    text: you are of legal age (18 years or older or otherwise of legal age in your resident jurisdiction)
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You may not use Services for any illegal or unauthorized purpose, including misusing the identity of another person.
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
name: eMudhra
provenance_date: '2026-11-09'
provider_name: eMudhra
provider_slug: emudhra
slug: emudhra-eligibility
source_date: '2026-11-09'
source_filename: emudhra-eligibility.yml
source_heading: Eligibility
source_page: https://emudhra.com/en-us/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: eMudhra\naid: emudhra\nurl: https://emudhra.com/en-us/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not and will not when using the Services be located in, under the\n    control of, or a national or resident of a U.S embargoed country or territory\nentity_types:\n- type: business\n  text: If You are entering into this Agreement on behalf of a company, organization or another legal entity (an\n    \"Entity\"), You are agreeing to this Agreement for that Entity\n- type: individual\n  text: You represent and warrant that you are\
  \ of legal age (18 years or older or otherwise of legal age in your\n    resident jurisdiction)\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You may not use Services for any illegal or unauthorized purpose, including misusing the identity of another\n    person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are of legal age (18 years or older or otherwise of legal age in your resident jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/emudhra/eligibility/emudhra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from eMudhra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PKI
- Digital Trust
- Enterprise Software
- Security
---
