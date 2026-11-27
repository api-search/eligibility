---
api_specs:
- filename: ona-api-reference-openapi-generated.yml
  format: yaml
  label: Ona API Reference API
  slug: api-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ona/openapi/_ae-authored/ona-api-reference-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual using the Site on behalf of an entity, you represent and warrant that you have the legal authority to bind such entity to these Terms
    type: individual
  minimum_age:
    text: The Site and the Site Materials are not directed to, or designed and intended, for use by children under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: use our Sites or Site Materials for any illegal or unauthorized purpose
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
name: Ona
provenance_date: '2026-11-10'
provider_name: Ona
provider_slug: ona
slug: ona-eligibility
source_date: '2026-11-10'
source_filename: ona-eligibility.yml
source_heading: Eligibility
source_page: https://ona.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ona\naid: ona\nurl: https://ona.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual using the Site on behalf of an entity, you represent and warrant that you have\n    the legal authority to bind such entity to these Terms\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: use our Sites or Site Materials for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site\
  \ and the Site Materials are not directed to, or designed and intended, for use by children under\n    the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/ona/eligibility/ona-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Ona's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Cloud
- Development
- Platform
- Automation
---
