---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only to be used for your personal non-commercial use and information.
    type: individual
  minimum_age:
    text: This Site is directed to be used by adults only.
    value: adults
  restricted_uses:
  - summary: Reselling products
    text: shall not be sold or resold for any/commercial reasons.
  - summary: Accessing systems without authorization
    text: accessing data not intended for you or logging onto a server or an account which you are not authorized to access
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
name: Uppercase
provenance_date: '2026-11-10'
provider_name: Uppercase
provider_slug: uppercase
slug: uppercase-eligibility
source_date: '2026-11-10'
source_filename: uppercase-eligibility.yml
source_heading: Eligibility
source_page: https://uppercase.co.in/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uppercase\naid: uppercase\nurl: https://uppercase.co.in/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only to be used for your personal non-commercial use and information.\nrestricted_uses:\n- summary: Reselling products\n  text: shall not be sold or resold for any/commercial reasons.\n- summary: Accessing systems without authorization\n  text: accessing data not intended for you or logging onto a server or an account which you are not authorized\n    to access\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adults\n  text: This Site is directed to be used by adults only.\n"
source_yaml_url: https://artifacts.apis.io/uppercase/eligibility/uppercase-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Uppercase's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Travel
- Luggage
- Backpacks
- E-Commerce
- Retail
- Sustainability
- Agentic Commerce
---
