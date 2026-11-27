---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You are not a person barred from receiving the Service under the laws of Canada, the United States, or other applicable jurisdiction
  entity_types:
  - text: If you open an account on behalf of a company, organization, or other entity, then (a) “you” includes you and that entity, and (b) you represent and warrant that you are authorized to grant all permissions and licenses provided in these Agreement and bind the entity to this Agreement
    type: business
  minimum_age:
    text: You are at least 18 years old and have the legal capacity to be bound by this Agreement
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: Client will not directly or indirectly export or re-export (including by transmission) any regulated technology to any country to which such activity is restricted by regulation or statute, without the prior written consent, if required, of the administrator of export laws.
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
name: Rhythmos
provenance_date: '2026-11-10'
provider_name: Rhythmos
provider_slug: rhythmos
slug: rhythmos-eligibility
source_date: '2026-11-10'
source_filename: rhythmos-eligibility.yml
source_heading: Eligibility
source_page: https://rhythmos.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rhythmos\naid: rhythmos\nurl: https://rhythmos.io/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You are not a person barred from receiving the Service under the laws of Canada, the United States, or other\n    applicable jurisdiction\nentity_types:\n- type: business\n  text: If you open an account on behalf of a company, organization, or other entity, then (a) “you” includes you\n    and that entity, and (b) you represent and warrant that you are authorized to grant all permissions and licenses\n    provided in these Agreement and bind the entity to this Agreement\n\
  restricted_uses:\n- summary: Export restrictions\n  text: Client will not directly or indirectly export or re-export (including by transmission) any regulated technology\n    to any country to which such activity is restricted by regulation or statute, without the prior written consent,\n    if required, of the administrator of export laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old and have the legal capacity to be bound by this Agreement\n"
source_yaml_url: https://artifacts.apis.io/rhythmos/eligibility/rhythmos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Rhythmos's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Energy
- Electric Vehicles
- EV Charging
- Grid
- Utilities
- Analytics
- Sustainability
- Clean Energy
---
