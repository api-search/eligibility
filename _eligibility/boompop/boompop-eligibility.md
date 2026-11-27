---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “Client.” means the Company or Organization entering into this agreement.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Firearms prohibited at events
    text: Clients and attendees are prohibited from bringing firearms to any event planned by BoomPop.
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
name: Boompop
provenance_date: '2026-11-09'
provider_name: Boompop
provider_slug: boompop
slug: boompop-eligibility
source_date: '2026-11-09'
source_filename: boompop-eligibility.yml
source_heading: Eligibility
source_page: https://boompop.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boompop\naid: boompop\nurl: https://boompop.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: “Client.” means the Company or Organization entering into this agreement.\nrestricted_uses:\n- summary: Firearms prohibited at events\n  text: Clients and attendees are prohibited from bringing firearms to any event planned by BoomPop.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/boompop/eligibility/boompop-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Boompop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Event Management
- Event Planning
- Corporate Events
- Hospitality
- Travel
- Software-as-a-Service
- Meetings and Events
---
