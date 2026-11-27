---
api_specs:
- filename: ayurak-com-openapi-generated.yml
  format: yaml
  label: ayurak-com API
  slug: ayurak-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ayurak-com/openapi/_ae-authored/ayurak-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age and have the legal capacity to enter into binding agreements.
    type: individual
  - text: The Platform is designed for business use; consumer protection laws may not apply.
    type: business
  minimum_age:
    text: You must be at least 18 years of age and have the legal capacity to enter into binding agreements.
    value: '18'
  restricted_uses:
  - summary: Illegal purpose or cyberattacks
    text: (j) Use the Platform for any illegal purpose , including to facilitate cyberattacks against third parties.
  - summary: Unlawful data processing
    text: (e) Use the Platform to process, store, or transmit data in violation of applicable laws, including data protection and export control laws;
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
name: ayurak-com
provenance_date: '2026-11-09'
provider_name: ayurak-com
provider_slug: ayurak-com
slug: ayurak-com-eligibility
source_date: '2026-11-09'
source_filename: ayurak-com-eligibility.yml
source_heading: Eligibility
source_page: https://ayurak.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ayurak-com\naid: ayurak-com\nurl: https://ayurak.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age and have the legal capacity to enter into binding agreements.\n- type: business\n  text: The Platform is designed for business use; consumer protection laws may not apply.\nrestricted_uses:\n- summary: Illegal purpose or cyberattacks\n  text: (j) Use the Platform for any illegal purpose , including to facilitate cyberattacks against third parties.\n- summary: Unlawful data processing\n\
  \  text: (e) Use the Platform to process, store, or transmit data in violation of applicable laws, including data\n    protection and export control laws;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age and have the legal capacity to enter into binding agreements.\n"
source_yaml_url: https://artifacts.apis.io/ayurak-com/eligibility/ayurak-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ayurak-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Security
- Healthcare
- Emergency Response
- Technology
---
