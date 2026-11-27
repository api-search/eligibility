---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: if you are an individual person, that you are at least 18 years of age and a resident of the US
  entity_types:
  - text: if you are an individual person, that you are at least 18 years of age and a resident of the US
    type: individual
  - text: if you are an organization, that you are validly organized under applicable US law, and the person completing this registration is authorized to enter into contracts on the entity’s behalf
    type: business
  minimum_age:
    text: if you are an individual person, that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You will not use the doxo Services or any of the doxo Services Materials other than for their intended purpose or in any way that is unlawful or harms us or our suppliers.
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
name: doxo
provenance_date: '2026-11-09'
provider_name: doxo
provider_slug: doxo
slug: doxo-eligibility
source_date: '2026-11-09'
source_filename: doxo-eligibility.yml
source_heading: Eligibility
source_page: https://www.doxo.com/w/legal/user/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: doxo\naid: doxo\nurl: https://www.doxo.com/w/legal/user/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: if you are an individual person, that you are at least 18 years of age and a resident of the US\nentity_types:\n- type: individual\n  text: if you are an individual person, that you are at least 18 years of age and a resident of the US\n- type: business\n  text: if you are an organization, that you are validly organized under applicable US law, and the person completing\n    this registration is authorized to enter into contracts on the entity’s behalf\n\
  restricted_uses:\n- summary: Unlawful or harmful use\n  text: You will not use the doxo Services or any of the doxo Services Materials other than for their intended purpose\n    or in any way that is unlawful or harms us or our suppliers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are an individual person, that you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/doxo/eligibility/doxo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from doxo's own page on 2026-11-09.
synthetic: false
tags:
- Bill Pay
- Fintech
- Consumer Services
- Payments
- Personal Finance
---
