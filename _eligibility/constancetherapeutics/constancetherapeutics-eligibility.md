---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We ship within the United States. Orders placed from outside the United States are not shipped automatically.
  entity_types:
  - text: Orders may be placed only by adults aged 21 and older.
    type: individual
  minimum_age:
    text: Orders may be placed only by adults aged 21 and older.
    value: '21'
  restricted_uses:
  - summary: Adults 21+ only
    text: Products are not for use or sale to persons under the age of 21.
  - summary: Not for pregnant or nursing use
    text: Hemp products should not be used if you are pregnant or nursing.
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
name: Constancetherapeutics
provenance_date: '2026-11-09'
provider_name: Constancetherapeutics
provider_slug: constancetherapeutics
slug: constancetherapeutics-eligibility
source_date: '2026-11-09'
source_filename: constancetherapeutics-eligibility.yml
source_heading: Eligibility
source_page: https://constancetherapeutics.com/utility/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Constancetherapeutics\naid: constancetherapeutics\nurl: https://constancetherapeutics.com/utility/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We ship within the United States. Orders placed from outside the United States are not shipped automatically.\nentity_types:\n- type: individual\n  text: Orders may be placed only by adults aged 21 and older.\nrestricted_uses:\n- summary: Adults 21+ only\n  text: Products are not for use or sale to persons under the age of 21.\n- summary: Not for pregnant or nursing use\n  text: Hemp products should not be used if\
  \ you are pregnant or nursing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: Orders may be placed only by adults aged 21 and older.\n"
source_yaml_url: https://artifacts.apis.io/constancetherapeutics/eligibility/constancetherapeutics-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Constancetherapeutics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cannabis
- Therapeutics
- CBD
- Health
---
