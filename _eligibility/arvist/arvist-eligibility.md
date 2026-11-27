---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for use in the United States only.
  minimum_age:
    text: The Site is not directed at children under the age of eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Under-18 users
    text: The Site is not directed at children under the age of eighteen (18) years old. If you are under eighteen (18) years old, you must immediately stop using the Site.
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
name: Arvist
provenance_date: '2026-11-09'
provider_name: Arvist
provider_slug: arvist
slug: arvist-eligibility
source_date: '2026-11-09'
source_filename: arvist-eligibility.yml
source_heading: Eligibility
source_page: https://arvist.ai/terms-and-condition/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arvist\naid: arvist\nurl: https://arvist.ai/terms-and-condition/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for use in the United States only.\nentity_types: []\nrestricted_uses:\n- summary: Under-18 users\n  text: The Site is not directed at children under the age of eighteen (18) years old. If you are under eighteen\n    (18) years old, you must immediately stop using the Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is not directed at children under the age of\
  \ eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/arvist/eligibility/arvist-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Arvist's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Computer Vision
- Artificial Intelligence
- Warehouse
- Supply Chain
- Logistics
- Quality Control
- Safety and Compliance
---
