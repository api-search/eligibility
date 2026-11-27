---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'თუ თქვენ რეგისტრირდებით იურიდიული პირის სახელით: თქვენ აცხადებთ, რომ გაქვთ უფლებამოსილება'
    type: business
  minimum_age:
    text: იყოს მინიმუმ 18 წლის ასაკის
    value: '18'
  restricted_uses:
  - summary: No use for competing products
    text: სერვისზე წვდომა ან სერვისის გამოყენება meni.ge-სთან კონკურენტული პროდუქტების ან სერვისების შექმნის ან მხარდაჭერის მიზნით
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
name: meni-ge
provenance_date: '2026-11-10'
provider_name: meni-ge
provider_slug: meni-ge
slug: meni-ge-eligibility
source_date: '2026-11-10'
source_filename: meni-ge-eligibility.yml
source_heading: Eligibility
source_page: https://meni.ge/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: meni-ge\naid: meni-ge\nurl: https://meni.ge/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'თუ თქვენ რეგისტრირდებით იურიდიული პირის სახელით: თქვენ აცხადებთ, რომ გაქვთ უფლებამოსილება'\nrestricted_uses:\n- summary: No use for competing products\n  text: სერვისზე წვდომა ან სერვისის გამოყენება meni.ge-სთან კონკურენტული პროდუქტების ან სერვისების შექმნის ან მხარდაჭერის\n    მიზნით\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: იყოს მინიმუმ 18\
  \ წლის ასაკის\n"
source_yaml_url: https://artifacts.apis.io/meni-ge/eligibility/meni-ge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from meni-ge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Point-of-Sale
- Inventory
- CRM
- Hospitality
- E-Commerce
---
