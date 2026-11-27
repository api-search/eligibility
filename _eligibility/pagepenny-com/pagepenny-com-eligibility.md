---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is for businesses and developers, not personal or household use.
    type: business
  - text: The Service is for businesses and developers, not personal or household use.
    type: developer
  minimum_age:
    text: You must be at least 18 and legally able to enter contracts.
    value: '18'
  restricted_uses:
  - summary: Forged or deceptive documents
    text: is a forged, counterfeit or deceptive document, such as fake invoices, receipts, certificates, IDs, or records presented as genuine to deceive anyone
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
name: pagepenny-com
provenance_date: '2026-11-10'
provider_name: pagepenny-com
provider_slug: pagepenny-com
slug: pagepenny-com-eligibility
source_date: '2026-11-10'
source_filename: pagepenny-com-eligibility.yml
source_heading: Eligibility
source_page: https://pagepenny.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pagepenny-com\naid: pagepenny-com\nurl: https://pagepenny.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Service is for businesses and developers, not personal or household use.\n- type: developer\n  text: The Service is for businesses and developers, not personal or household use.\nrestricted_uses:\n- summary: Forged or deceptive documents\n  text: is a forged, counterfeit or deceptive document, such as fake invoices, receipts, certificates, IDs, or records\n    presented as genuine to deceive anyone\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter contracts.\n"
source_yaml_url: https://artifacts.apis.io/pagepenny-com/eligibility/pagepenny-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from pagepenny-com's own page on 2026-11-10.
synthetic: false
tags:
- Templates
- Developers
- Automation
---
