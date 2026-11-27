---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old.
    type: individual
  - text: Service providers must be legally registered to operate in their country (KvK in the Netherlands, equivalent elsewhere)
    type: business
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We match clients with verified local professionals through a protocol-based matching system.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: astranl-com
provenance_date: '2026-11-09'
provider_name: astranl-com
provider_slug: astranl-com
slug: astranl-com-eligibility
source_date: '2026-11-09'
source_filename: astranl-com-eligibility.yml
source_heading: Eligibility
source_page: https://astranl.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: astranl-com\naid: astranl-com\nurl: https://astranl.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old.\n- type: business\n  text: Service providers must be legally registered to operate in their country (KvK in the Netherlands, equivalent\n    elsewhere)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We match clients with verified local professionals through a protocol-based matching system.\nminimum_age:\n  value: '18'\n  text: You must be\
  \ at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/astranl-com/eligibility/astranl-com-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from astranl-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Coordination
- Payments
- Platform
- NL
---
