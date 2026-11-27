---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For business customers only, to the extent permitted by law, you agree to cover third-party claims and reasonable defense costs caused by your unlawful use of Benchlight
    type: business
  minimum_age:
    text: You must be at least 18 and authorized to act for the business whose account, website or connected services you manage.
    value: '18'
  restricted_uses:
  - summary: Sensitive records
    text: Do not use ordinary Benchlight forms for health records, card numbers, government ID numbers or other sensitive records requiring a separate arrangement.
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
name: Benchlight
provenance_date: '2026-11-09'
provider_name: Benchlight
provider_slug: benchlight-dev
slug: benchlight-dev-eligibility
source_date: '2026-11-09'
source_filename: benchlight-dev-eligibility.yml
source_heading: Eligibility
source_page: https://benchlight.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Benchlight\naid: benchlight-dev\nurl: https://benchlight.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: For business customers only, to the extent permitted by law, you agree to cover third-party claims and reasonable\n    defense costs caused by your unlawful use of Benchlight\nrestricted_uses:\n- summary: Sensitive records\n  text: Do not use ordinary Benchlight forms for health records, card numbers, government ID numbers or other sensitive\n    records requiring a separate arrangement.\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and authorized to act for the business whose account, website or connected services\n    you manage.\n"
source_yaml_url: https://artifacts.apis.io/benchlight-dev/eligibility/benchlight-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Benchlight's own page on 2026-11-09.
synthetic: false
tags:
- Website Builder
- Small Business
- Hosting
- No-Code
- Software-as-a-Service
---
