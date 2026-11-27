---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using Acutis Go on behalf of an organization, you represent that you are authorized to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Install only on owned or authorized devices
    text: Install the agent only on devices you own or are authorized to administer.
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
name: Acutis Go
provenance_date: '2026-11-09'
provider_name: Acutis Go
provider_slug: acutisgo-com
slug: acutisgo-com-eligibility
source_date: '2026-11-09'
source_filename: acutisgo-com-eligibility.yml
source_heading: Eligibility
source_page: https://acutisgo.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Acutis Go\naid: acutisgo-com\nurl: https://acutisgo.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using Acutis Go on behalf of an organization, you represent that you are authorized to bind that\n    organization.\nrestricted_uses:\n- summary: Install only on owned or authorized devices\n  text: Install the agent only on devices you own or are authorized to administer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acutisgo-com/eligibility/acutisgo-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Acutis Go's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Networks
- Agents
- Observability
- Free
- Dashboards
---
