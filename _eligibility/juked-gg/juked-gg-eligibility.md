---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are thirteen (13) years of age or above
    type: individual
  minimum_age:
    text: you are thirteen (13) years of age or above
    value: '13'
  restricted_uses:
  - summary: Private use only
    text: not for any commercial use, such as marketing or sale of goods or Services
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
name: Buffd
provenance_date: '2026-11-09'
provider_name: Buffd
provider_slug: juked-gg
slug: juked-gg-eligibility
source_date: '2026-11-09'
source_filename: juked-gg-eligibility.yml
source_heading: Eligibility
source_page: https://juked.gg/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buffd\naid: juked-gg\nurl: https://juked.gg/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are thirteen (13) years of age or above\nrestricted_uses:\n- summary: Private use only\n  text: not for any commercial use, such as marketing or sale of goods or Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are thirteen (13) years of age or above\n"
source_yaml_url: https://artifacts.apis.io/juked-gg/eligibility/juked-gg-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Buffd's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
