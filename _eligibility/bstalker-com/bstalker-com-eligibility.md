---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful use or source platform violations
    text: use the Service to violate any law, the rights of others, or the terms of any source platform
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Eligible new accounts may start one 3 -day full-access trial at checkout. A payment method is required to start it
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BStalker
provenance_date: '2026-11-09'
provider_name: BStalker
provider_slug: bstalker-com
slug: bstalker-com-eligibility
source_date: '2026-11-09'
source_filename: bstalker-com-eligibility.yml
source_heading: Eligibility
source_page: https://bstalker.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BStalker\naid: bstalker-com\nurl: https://bstalker.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No unlawful use or source platform violations\n  text: use the Service to violate any law, the rights of others, or the terms of any source platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Eligible new accounts may start one 3 -day full-access trial at checkout. A payment method is required to\n    start it\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bstalker-com/eligibility/bstalker-com-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from BStalker's own page on 2026-11-09.
synthetic: false
tags:
- Marketplace
- Auctions
- Liquidation
- Aggregator
- BStalker
---
