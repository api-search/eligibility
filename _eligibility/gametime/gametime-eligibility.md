---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for your personal, noncommercial use only and as permitted by the features of the Service.
    type: individual
  - text: If you open a Gametime United account on behalf of a company, organization, or other entity, then (a) “you” includes you and that entity
    type: business
  minimum_age:
    text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.
    value: '13'
  restricted_uses:
  - summary: Under-13 use prohibited
    text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.
  - summary: Commercial solicitation
    text: using the Service for any commercial solicitation purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: When creating your account, you must provide accurate and complete information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Gametime
provenance_date: '2026-11-09'
provider_name: Gametime
provider_slug: gametime
slug: gametime-eligibility
source_date: '2026-11-09'
source_filename: gametime-eligibility.yml
source_heading: Eligibility
source_page: https://gametime.co/policies/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gametime\naid: gametime\nurl: https://gametime.co/policies/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for your personal, noncommercial use only and as permitted by the features of the Service.\n- type: business\n  text: If you open a Gametime United account on behalf of a company, organization, or other entity, then (a) “you”\n    includes you and that entity\nrestricted_uses:\n- summary: Under-13 use prohibited\n  text: Any use or access to the Service by anyone under 13 is strictly prohibited\
  \ and in violation of this Agreement.\n- summary: Commercial solicitation\n  text: using the Service for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: When creating your account, you must provide accurate and complete information.\nminimum_age:\n  value: '13'\n  text: Any use or access to the Service by anyone under 13 is strictly prohibited and in violation of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/gametime/eligibility/gametime-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Gametime's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Ticketing
- Event
- Ticketing Marketplace
- Sports
- Live Entertainment
- Mobile
---
