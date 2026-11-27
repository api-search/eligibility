---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: licensed by an individual or corporate customer
    type: individual
  - text: licensed by an individual or corporate customer
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive personal information
    text: submitting any sensitive personal information through the Anaqua Site, including the chatbot
  - summary: No export-controlled submissions
    text: submitting any information through the Anaqua Site that is subject to export control laws
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
name: Anaqua
provenance_date: '2026-11-09'
provider_name: Anaqua
provider_slug: anaqua
slug: anaqua-eligibility
source_date: '2026-11-09'
source_filename: anaqua-eligibility.yml
source_heading: Eligibility
source_page: https://www.anaqua.com/legal-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anaqua\naid: anaqua\nurl: https://www.anaqua.com/legal-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: licensed by an individual or corporate customer\n- type: business\n  text: licensed by an individual or corporate customer\nrestricted_uses:\n- summary: No sensitive personal information\n  text: submitting any sensitive personal information through the Anaqua Site, including the chatbot\n- summary: No export-controlled submissions\n  text: submitting any information through the Anaqua Site that is subject to export control\
  \ laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anaqua/eligibility/anaqua-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Anaqua's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Intellectual Property
- IP Management
- Patents
- Trademarks
- Legal Tech
- Software-as-a-Service
- Innovation Management
---
