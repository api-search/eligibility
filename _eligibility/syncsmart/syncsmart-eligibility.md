---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU SHOULD BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.
    value: '18'
  restricted_uses:
  - summary: Acceptable use policy
    text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content
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
name: SyncSmart
provenance_date: '2026-11-10'
provider_name: SyncSmart
provider_slug: syncsmart
slug: syncsmart-eligibility
source_date: '2026-11-10'
source_filename: syncsmart-eligibility.yml
source_heading: Eligibility
source_page: https://www.syncsmart.io/terms-of-use-syncsmart
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SyncSmart\naid: syncsmart\nurl: https://www.syncsmart.io/terms-of-use-syncsmart\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Acceptable use policy\n  text: You agree not to use the Site to collect, upload, transmit, display, or distribute any User Content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU SHOULD BE AT LEAST 18 YEARS OF AGE TO ACCESS THE SITE.\n"
source_yaml_url: https://artifacts.apis.io/syncsmart/eligibility/syncsmart-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from SyncSmart's own page on 2026-11-10.
synthetic: false
tags:
- Integration
- HubSpot
- Marketing
- Sales
- Automation
---
