---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You receive a limited, non-exclusive, non-transferable, revocable licence to use the Service for your internal business purposes, in line with your Subscription plan.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: Use the Service in violation of applicable laws or regulations
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
name: Quaisr
provenance_date: '2026-11-10'
provider_name: Quaisr
provider_slug: quaisr
slug: quaisr-eligibility
source_date: '2026-11-10'
source_filename: quaisr-eligibility.yml
source_heading: Eligibility
source_page: https://quaisr.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quaisr\naid: quaisr\nurl: https://quaisr.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You receive a limited, non-exclusive, non-transferable, revocable licence to use the Service for your internal\n    business purposes, in line with your Subscription plan.\nrestricted_uses:\n- summary: Unlawful use\n  text: Use the Service in violation of applicable laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/quaisr/eligibility/quaisr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Quaisr's own page on 2026-11-10.
synthetic: false
tags:
- SimOps
- Engineering
- Simulation
- Connectivity
---
