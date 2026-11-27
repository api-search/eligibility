---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In order to register for an Account, you must be aged 18 or over.
    type: individual
  minimum_age:
    text: In order to register for an Account, you must be aged 18 or over.
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful conduct
    text: use the Website in any way that breaches these Terms or any applicable local, national or international law or regulation
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
name: WealthObjects
provenance_date: '2026-11-10'
provider_name: WealthObjects
provider_slug: wealthobjects
slug: wealthobjects-eligibility
source_date: '2026-11-10'
source_filename: wealthobjects-eligibility.yml
source_heading: Eligibility
source_page: https://wealthobjectsplatform.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WealthObjects\naid: wealthobjects\nurl: https://wealthobjectsplatform.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In order to register for an Account, you must be aged 18 or over.\nrestricted_uses:\n- summary: Unlawful or harmful conduct\n  text: use the Website in any way that breaches these Terms or any applicable local, national or international\n    law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to register for\
  \ an Account, you must be aged 18 or over.\n"
source_yaml_url: https://artifacts.apis.io/wealthobjects/eligibility/wealthobjects-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from WealthObjects's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Wealth Management
- API Platform
- Data Aggregation
- Compliance
---
