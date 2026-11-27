---
api_specs:
- filename: overleaf-openapi-generated.yml
  format: yaml
  label: Overleaf API
  slug: overleaf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/overleaf/openapi/_ae-authored/overleaf-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may use the Services only if you have the power to form a contract with us and are not barred under any applicable laws from doing so, including if you are too young to enter into a binding contract or because you are based in a sanctioned country or are on a sanctions list.
  entity_types:
  - text: You may use the Services only if you have the power to form a contract with us
    type: individual
  - text: If you are using the Services on behalf of an organization, you are agreeing to these Terms for that organization
    type: business
  minimum_age:
    text: too young to enter into a binding contract
    value: null
  restricted_uses:
  - summary: Accounts only in own name
    text: You must only register accounts in your own name, and never for resale.
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
name: Overleaf
provenance_date: '2026-11-10'
provider_name: Overleaf
provider_slug: overleaf
slug: overleaf-eligibility
source_date: '2026-11-10'
source_filename: overleaf-eligibility.yml
source_heading: Eligibility
source_page: https://www.overleaf.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Overleaf\naid: overleaf\nurl: https://www.overleaf.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may use the Services only if you have the power to form a contract with us and are not barred under\n    any applicable laws from doing so, including if you are too young to enter into a binding contract or because\n    you are based in a sanctioned country or are on a sanctions list.\nentity_types:\n- type: individual\n  text: You may use the Services only if you have the power to form a contract with us\n- type: business\n  text: If you are using the\
  \ Services on behalf of an organization, you are agreeing to these Terms for that organization\nrestricted_uses:\n- summary: Accounts only in own name\n  text: You must only register accounts in your own name, and never for resale.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: too young to enter into a binding contract\n"
source_yaml_url: https://artifacts.apis.io/overleaf/eligibility/overleaf-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Overleaf's own page on 2026-11-10.
synthetic: false
tags:
- Collaboration
- LaTeX
- Cloud
- Academic
- Writing
- Company
---
