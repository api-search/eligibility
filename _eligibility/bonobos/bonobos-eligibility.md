---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'International Use: We control and operate the Services from the United States... You agree ... you are not a national of, or resident within any of the countries that are subject to trade embargo'
  entity_types:
  - text: You may access or use the Services only if you are 18 years or older, are capable of forming a binding contract with us
    type: individual
  minimum_age:
    text: You may access or use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: The Services may be used only for lawful purposes and in accordance with these Terms.
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
name: Bonobos
provenance_date: '2026-11-09'
provider_name: Bonobos
provider_slug: bonobos
slug: bonobos-eligibility
source_date: '2026-11-09'
source_filename: bonobos-eligibility.yml
source_heading: Eligibility
source_page: https://bonobos.com/pages/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bonobos\naid: bonobos\nurl: https://bonobos.com/pages/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'International Use: We control and operate the Services from the United States... You agree ... you are\n    not a national of, or resident within any of the countries that are subject to trade embargo'\nentity_types:\n- type: individual\n  text: You may access or use the Services only if you are 18 years or older, are capable of forming a binding contract\n    with us\nrestricted_uses:\n- summary: Unlawful use\n  text: The Services may be used\
  \ only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may access or use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/bonobos/eligibility/bonobos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Bonobos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Retail
- E-Commerce
- Apparel
- Menswear
- Fashion
- Direct to Consumer
---
