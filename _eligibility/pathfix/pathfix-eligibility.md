---
api_specs:
- filename: pathfix-openapi-generated.yml
  format: yaml
  label: Pathfix API
  slug: pathfix-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pathfix/openapi/_ae-authored/pathfix-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You (being a person or legal entity who is a user or subscriber of our Services)
    type: individual
  - text: If You are signing up as a company, organization or any other legal entity (“Entity”), you are agreeing to this agreement for that Entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Acceptable use restrictions
    text: You are responsible and liable for all uses of the Services under Your account including without limitation, compliance with all applicable laws and regulations and third party terms.
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
name: Pathfix
provenance_date: '2026-11-10'
provider_name: Pathfix
provider_slug: pathfix
slug: pathfix-eligibility
source_date: '2026-11-10'
source_filename: pathfix-eligibility.yml
source_heading: Eligibility
source_page: https://pathfix.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pathfix\naid: pathfix\nurl: https://pathfix.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You (being a person or legal entity who is a user or subscriber of our Services)\n- type: business\n  text: If You are signing up as a company, organization or any other legal entity (“Entity”), you are agreeing\n    to this agreement for that Entity\nrestricted_uses:\n- summary: Acceptable use restrictions\n  text: You are responsible and liable for all uses of the Services under Your account including without limitation,\n    compliance\
  \ with all applicable laws and regulations and third party terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pathfix/eligibility/pathfix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pathfix's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Integration Platform
- OAuth
- Automation
- API Management
- Authentication
---
