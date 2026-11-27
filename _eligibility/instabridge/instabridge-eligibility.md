---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Primary Provider Mobile Services are available only to users in the United States.
  entity_types:
  - text: You have the right to employ the Services for personal or non-commercial use.
    type: individual
  - text: Where User enters into this Agreement on behalf of a company or other organization, User represents and warrants that User has authority to act on behalf of that entity
    type: business
  minimum_age:
    text: User is of the legally required age in the jurisdiction in which User resides
    value: null
  restricted_uses:
  - summary: Non-personal or permanent tethering
    text: Permanent tethering or use of Services in routers or modems.
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
name: instabridge
provenance_date: '2026-11-09'
provider_name: instabridge
provider_slug: instabridge
slug: instabridge-eligibility
source_date: '2026-11-09'
source_filename: instabridge-eligibility.yml
source_heading: Eligibility
source_page: https://instabridge.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: instabridge\naid: instabridge\nurl: https://instabridge.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Primary Provider Mobile Services are available only to users in the United States.\nentity_types:\n- type: individual\n  text: You have the right to employ the Services for personal or non-commercial use.\n- type: business\n  text: Where User enters into this Agreement on behalf of a company or other organization, User represents and\n    warrants that User has authority to act on behalf of that entity\nrestricted_uses:\n- summary: Non-personal or permanent\
  \ tethering\n  text: Permanent tethering or use of Services in routers or modems.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: User is of the legally required age in the jurisdiction in which User resides\n"
source_yaml_url: https://artifacts.apis.io/instabridge/eligibility/instabridge-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from instabridge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wi-Fi
- eSIM
- Connectivity
- Mobile Data
- Telecommunications
- Travel
- VPN
---
