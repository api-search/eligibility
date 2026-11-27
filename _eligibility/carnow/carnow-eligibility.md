---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: signed by an authorized representative of your company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive content and misuse
    text: 'Neither Customer nor its Users shall use the Subscription Service to:'
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
name: CarNow
provenance_date: '2026-11-09'
provider_name: CarNow
provider_slug: carnow
slug: carnow-eligibility
source_date: '2026-11-09'
source_filename: carnow-eligibility.yml
source_heading: Eligibility
source_page: https://www.carnow.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CarNow\naid: carnow\nurl: https://www.carnow.com/eula/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: signed by an authorized representative of your company\nrestricted_uses:\n- summary: Unlawful or abusive content and misuse\n  text: 'Neither Customer nor its Users shall use the Subscription Service to:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carnow/eligibility/carnow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CarNow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Digital Retail
- Dealership
- Conversational Commerce
- Artificial Intelligence
- Lead Generation
- Chat
---
