---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: You must be at least 18 years old and a resident of Australia to use our services.
  entity_types:
  - text: You must be at least 18 years old and a resident of Australia to use our services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and a resident of Australia to use our services.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: you will use our website and services only for lawful purposes and in accordance with these terms
  - summary: No fraudulent or harmful use
    text: use our services in any way that is unlawful, fraudulent or harmful
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
name: Arthr
provenance_date: '2026-11-09'
provider_name: Arthr
provider_slug: arthr-com-au
slug: arthr-com-au-eligibility
source_date: '2026-11-09'
source_filename: arthr-com-au-eligibility.yml
source_heading: Eligibility
source_page: https://www.arthr.com.au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arthr\naid: arthr-com-au\nurl: https://www.arthr.com.au/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: You must be at least 18 years old and a resident of Australia to use our services.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and a resident of Australia to use our services.\nrestricted_uses:\n- summary: Lawful purposes only\n  text: you will use our website and services only for lawful purposes and in accordance with these terms\n- summary: No fraudulent or harmful use\n  text: use our services in any way that is unlawful, fraudulent\
  \ or harmful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and a resident of Australia to use our services.\n"
source_yaml_url: https://artifacts.apis.io/arthr-com-au/eligibility/arthr-com-au-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Arthr's own page on 2026-11-09.
synthetic: false
tags:
- Mortgage
- Brokerage
- Artificial Intelligence
- Australia
- Fintech
---
