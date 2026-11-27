---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer shall not permit any third party to access or use the System in... a country subject to United Nations Security Council, United States embargo (as of the Effective Date, Crimea region of Ukraine, Cuba, Iran, North Korea, Sudan, and Syria).
  entity_types:
  - text: (c) it is a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized to do business pursuant to applicable law.
    type: business
  minimum_age:
    text: the sole proprietorship of an individual 18 years or older
    value: '18'
  restricted_uses:
  - summary: No competitive builds
    text: access the System in order to build a competitive product or service
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
name: Klamp.ai
provenance_date: '2026-11-09'
provider_name: Klamp.ai
provider_slug: klamp
slug: klamp-eligibility
source_date: '2026-11-09'
source_filename: klamp-eligibility.yml
source_heading: Eligibility
source_page: https://klamp.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klamp.ai\naid: klamp\nurl: https://klamp.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer shall not permit any third party to access or use the System in... a country subject to United\n    Nations Security Council, United States embargo (as of the Effective Date, Crimea region of Ukraine, Cuba, Iran,\n    North Korea, Sudan, and Syria).\nentity_types:\n- type: business\n  text: (c) it is a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized\n    to do business pursuant to applicable law.\nrestricted_uses:\n\
  - summary: No competitive builds\n  text: access the System in order to build a competitive product or service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the sole proprietorship of an individual 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/klamp/eligibility/klamp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Klamp.ai's own page on 2026-11-09.
synthetic: false
tags:
- Integration
- iPaaS
- Data Migration
- Software-as-a-Service
- Embedded Solutions
---
