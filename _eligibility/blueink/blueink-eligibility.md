---
api_specs:
- filename: blueink-openapi-generated.yml
  format: yaml
  label: BlueInk Technologies API
  slug: blueink-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blueink/openapi/_ae-authored/blueink-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents it is not located in a country subject to a U.S. government embargo; no served list is stated.
  entity_types:
  - text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that you have the authority to commit the entity to the Agreement
    type: business
  - text: You may only use this Site and the Services if you are 18 years of age or older, able to legally agree to these Terms
    type: individual
  minimum_age:
    text: You may only use this Site and the Services if you are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Illegal or misleading purposes
    text: use or permit the Services to be used for any illegal or misleading purpose
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
name: BlueInk Technologies
provenance_date: '2026-11-09'
provider_name: BlueInk Technologies
provider_slug: blueink
slug: blueink-eligibility
source_date: '2026-11-09'
source_filename: blueink-eligibility.yml
source_heading: Eligibility
source_page: https://www.blueink.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlueInk Technologies\naid: blueink\nurl: https://www.blueink.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents it is not located in a country subject to a U.S. government embargo; no served list\n    is stated.\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a company or other legal entity, you represent that\n    you have the authority to commit the entity to the Agreement\n- type: individual\n  text: You may only use this Site and the Services if you are 18 years of age or older, able to legally agree\
  \ to\n    these Terms\nrestricted_uses:\n- summary: Illegal or misleading purposes\n  text: use or permit the Services to be used for any illegal or misleading purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may only use this Site and the Services if you are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/blueink/eligibility/blueink-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BlueInk Technologies's own page on 2026-11-09.
synthetic: false
tags:
- E-Signature
- Government
- Education
- Enterprise
- Compliance
- Workflows
- Integration
---
