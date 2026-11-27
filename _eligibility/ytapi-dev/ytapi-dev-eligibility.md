---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for a business, you will indemnify us and our contractors against claims, damages, and reasonable legal costs arising from your use of the data
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Resale or white-label
    text: resell or white-label the Service without our written permission
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Signup is by a one-time code sent to your email, or by Google or GitHub.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ytapi-dev
provenance_date: '2026-11-10'
provider_name: ytapi-dev
provider_slug: ytapi-dev
slug: ytapi-dev-eligibility
source_date: '2026-11-10'
source_filename: ytapi-dev-eligibility.yml
source_heading: Eligibility
source_page: https://ytapi.dev/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ytapi-dev\naid: ytapi-dev\nurl: https://ytapi.dev/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for a business, you will indemnify us and our contractors against claims, damages,\n    and reasonable legal costs arising from your use of the data\nrestricted_uses:\n- summary: Resale or white-label\n  text: resell or white-label the Service without our written permission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Signup is by a one-time code sent to your email, or by\
  \ Google or GitHub.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ytapi-dev/eligibility/ytapi-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ytapi-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Transcripts
- YouTube
---
