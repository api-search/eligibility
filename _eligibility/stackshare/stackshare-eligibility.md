---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service only if you are at least eighteen (18) years old and can form a binding contract with StackShare
    type: individual
  minimum_age:
    text: You may use the Service only if you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Unlawful purposes
    text: use the Service for any unlawful purposes or for promotion of illegal activities
  - summary: Competing offering
    text: access or use the Service or any Content to create or assist in the creation of a product, service or other offering the competes with the Service.
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
name: StackShare
provenance_date: '2026-11-10'
provider_name: StackShare
provider_slug: stackshare
slug: stackshare-eligibility
source_date: '2026-11-10'
source_filename: stackshare-eligibility.yml
source_heading: Eligibility
source_page: https://stackshare.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StackShare\naid: stackshare\nurl: https://stackshare.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service only if you are at least eighteen (18) years old and can form a binding contract\n    with StackShare\nrestricted_uses:\n- summary: Unlawful purposes\n  text: use the Service for any unlawful purposes or for promotion of illegal activities\n- summary: Competing offering\n  text: access or use the Service or any Content to create or assist in the creation of a product, service or other\n    offering the\
  \ competes with the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Service only if you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/stackshare/eligibility/stackshare-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from StackShare's own page on 2026-11-10.
synthetic: false
tags:
- Developer Tools
- Software Discovery
- Tech Stacks
---
