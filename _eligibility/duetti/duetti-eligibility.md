---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (c) neither you nor any entity you represent is subject to any economic sanctions, embargoes, or other trade restrictions administered by the U.S. government (including the Specially Designated Nationals and Blocked Persons List), the United Kingdom, the European Union, or any of its member states.
  entity_types:
  - text: The Services are intended for business use only and are not available to consumers (individuals acting for purposes outside of their trade, business, craft, or profession).
    type: business
  minimum_age:
    text: you are at least 13 years of age (or, if higher, the age of majority or contractual capacity in your jurisdiction)
    value: '13'
  restricted_uses:
  - summary: Use by consumers
    text: You are not authorized to use the Services as a consumer.
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
name: Duetti
provenance_date: '2026-11-09'
provider_name: Duetti
provider_slug: duetti
slug: duetti-eligibility
source_date: '2026-11-09'
source_filename: duetti-eligibility.yml
source_heading: Eligibility
source_page: https://www.duetti.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Duetti\naid: duetti\nurl: https://www.duetti.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: (c) neither you nor any entity you represent is subject to any economic sanctions, embargoes, or other trade\n    restrictions administered by the U.S. government (including the Specially Designated Nationals and Blocked Persons\n    List), the United Kingdom, the European Union, or any of its member states.\nentity_types:\n- type: business\n  text: The Services are intended for business use only and are not available to consumers (individuals acting for\n    purposes outside of\
  \ their trade, business, craft, or profession).\nrestricted_uses:\n- summary: Use by consumers\n  text: You are not authorized to use the Services as a consumer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are at least 13 years of age (or, if higher, the age of majority or contractual capacity in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/duetti/eligibility/duetti-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Duetti's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Music Rights
- Royalties
- Catalog Acquisition
- Music Finance
- Publishing
- Distribution
- Creator Economy
- Entertainment
---
