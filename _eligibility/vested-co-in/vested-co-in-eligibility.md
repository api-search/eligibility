---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any natural or legal person (whether a registered user or otherwise) who accesses the Website
    type: individual
  minimum_age:
    text: INDIVIDUALS UNDER THE AGE OF 18 ARE NOT PERMITTED TO SUBSCRIBE TO ANY OF OUR SERVICES.
    value: '18'
  restricted_uses:
  - summary: Personal noncommercial use only
    text: your subscription to our Services is only valid for your personal, noncommercial use and may not be shared with others
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: the grant or denial to avail of the services is at the complete and sole discretion of the partner platforms, who may reject or put hold your application in its sole discretion and judgment
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vested
provenance_date: '2026-11-10'
provider_name: Vested
provider_slug: vested-co-in
slug: vested-co-in-eligibility
source_date: '2026-11-10'
source_filename: vested-co-in-eligibility.yml
source_heading: Eligibility
source_page: https://vestedfinance.com/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vested\naid: vested-co-in\nurl: https://vestedfinance.com/legal/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: any natural or legal person (whether a registered user or otherwise) who accesses the Website\nrestricted_uses:\n- summary: Personal noncommercial use only\n  text: your subscription to our Services is only valid for your personal, noncommercial use and may not be shared\n    with others\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: the grant or denial to\
  \ avail of the services is at the complete and sole discretion of the partner platforms,\n    who may reject or put hold your application in its sole discretion and judgment\nminimum_age:\n  value: '18'\n  text: INDIVIDUALS UNDER THE AGE OF 18 ARE NOT PERMITTED TO SUBSCRIBE TO ANY OF OUR SERVICES.\n"
source_yaml_url: https://artifacts.apis.io/vested-co-in/eligibility/vested-co-in-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Vested's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Investment
- Global Markets
- India
- Platform
---
