---
api_specs:
- filename: underlayerhq-com-openapi-generated.yml
  format: yaml
  label: underlayerhq-com API
  slug: underlayerhq-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/underlayerhq-com/openapi/_ae-authored/underlayerhq-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you're not located in, and won't use the Services from, a country or territory subject to comprehensive UAE or applicable international trade sanctions
  entity_types:
  - text: You must be at least 18 years old, and have authority to bind your organization if you're signing up on its behalf, to use the Services.
    type: individual
  - text: if you're acting for an organization, on behalf of that organization, and you confirm you have authority to do so.
    type: business
  minimum_age:
    text: You must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing content
    text: Generate, host, or deliver content that is unlawful, defamatory, infringing, or that violates UAE Federal Decree-Law No. 34 of 2021 on Combating Rumors and Cybercrimes or equivalent law in your jurisdiction.
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
name: underlayerhq-com
provenance_date: '2026-11-10'
provider_name: underlayerhq-com
provider_slug: underlayerhq-com
slug: underlayerhq-com-eligibility
source_date: '2026-11-10'
source_filename: underlayerhq-com-eligibility.yml
source_heading: Eligibility
source_page: https://underlayerhq.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: underlayerhq-com\naid: underlayerhq-com\nurl: https://underlayerhq.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you're not located in, and won't use the Services from, a country or territory subject\n    to comprehensive UAE or applicable international trade sanctions\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, and have authority to bind your organization if you're signing up on\n    its behalf, to use the Services.\n- type: business\n  text: if you're acting for an organization, on behalf of that organization, and\
  \ you confirm you have authority\n    to do so.\nrestricted_uses:\n- summary: Unlawful or infringing content\n  text: Generate, host, or deliver content that is unlawful, defamatory, infringing, or that violates UAE Federal\n    Decree-Law No. 34 of 2021 on Combating Rumors and Cybercrimes or equivalent law in your jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/underlayerhq-com/eligibility/underlayerhq-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from underlayerhq-com's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Software-as-a-Service
- Training
- LMS
- Embeddings
---
