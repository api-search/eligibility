---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Företaget har köpt Novus i Fortnox och du har en av licenserna tilldelad.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Du har en egen inloggning i Fortnox för företaget.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: novusmcp-se
provenance_date: '2026-11-10'
provider_name: novusmcp-se
provider_slug: novusmcp-se
slug: novusmcp-se-eligibility
source_date: '2026-11-10'
source_filename: novusmcp-se-eligibility.yml
source_heading: Eligibility
source_page: https://novusmcp.se/villkor
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: novusmcp-se\naid: novusmcp-se\nurl: https://novusmcp.se/villkor\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Företaget har köpt Novus i Fortnox och du har en av licenserna tilldelad.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Du har en egen inloggning i Fortnox för företaget.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/novusmcp-se/eligibility/novusmcp-se-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from novusmcp-se's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Accounting
- Artificial Intelligence
- Integration
- Fortnox
- Sweden
---
