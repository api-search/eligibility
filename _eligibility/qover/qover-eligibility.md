---
api_specs:
- filename: postman.yaml
  format: yaml
  label: Qover Embedded Insurance API
  slug: qover-embedded-insurance-api
  spec_type: Postman
  url: https://docs.qover.com/
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The online insurance contract subscription services potentially offered via the Site are reserved for adults.
    type: individual
  minimum_age:
    text: The online insurance contract subscription services potentially offered via the Site are reserved for adults.
    value: adults
  restricted_uses:
  - summary: Insurance subscription reserved for adults
    text: The online insurance contract subscription services potentially offered via the Site are reserved for adults.
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
name: Qover
provenance_date: '2026-11-10'
provider_name: Qover
provider_slug: qover
slug: qover-eligibility
source_date: '2026-11-10'
source_filename: qover-eligibility.yml
source_heading: Eligibility
source_page: https://storage.googleapis.com/qover-assets/documents/terms/Terms-of-use_EN.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qover\naid: qover\nurl: https://storage.googleapis.com/qover-assets/documents/terms/Terms-of-use_EN.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The online insurance contract subscription services potentially offered via the Site are reserved for adults.\nrestricted_uses:\n- summary: Insurance subscription reserved for adults\n  text: The online insurance contract subscription services potentially offered via the Site are reserved for adults.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: adults\n  text: The online insurance contract subscription services potentially offered via the Site are reserved for adults.\n"
source_yaml_url: https://artifacts.apis.io/qover/eligibility/qover-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Qover's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Insurtech
- Insurance
- Embedded Insurance
- Claims
- Policy
- Fintech
- Belgium
---
