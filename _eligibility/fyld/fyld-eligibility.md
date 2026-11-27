---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Subject to the above paragraph, as you are a business user, in no event shall we be liable to you for any indirect or consequential losses
    type: business
  minimum_age:
    text: The Site is intended for use only by persons who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Work-related use only
    text: use the platform for any other purpose than in connection with your employment or work being undertaken on behalf of the Company.
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
name: FYLD
provenance_date: '2026-11-09'
provider_name: FYLD
provider_slug: fyld
slug: fyld-eligibility
source_date: '2026-11-09'
source_filename: fyld-eligibility.yml
source_heading: Eligibility
source_page: https://fyld.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FYLD\naid: fyld\nurl: https://fyld.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Subject to the above paragraph, as you are a business user, in no event shall we be liable to you for any\n    indirect or consequential losses\nrestricted_uses:\n- summary: Work-related use only\n  text: use the platform for any other purpose than in connection with your employment or work being undertaken\n    on behalf of the Company.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: The Site is intended for use only by persons who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/fyld/eligibility/fyld-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from FYLD's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Industrial, Energy & Iot
- Field Operations
- Utilities
- Energy
- Construction
- Artificial Intelligence
- Frontline Intelligence
- Infrastructure
- Safety
---
