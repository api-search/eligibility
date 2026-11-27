---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The products and services displayed on the Site may not be available for purchase in your particular country or locality.
  entity_types:
  - text: We offer travel agents hotels, flight bookings and travel services purchased from Us.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Sanctioned parties
    text: neither You nor your stakeholders or directors, or Ultimate Beneficial Owners are on the Office of Foreign Assets Control (OFAC), Specially Designated Nationals (SDN), Office of Financial Sanctions Implementation (OFSI) European Union (EU) United Nations (UN) or Blocked Persons list.
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
name: TBO.com
provenance_date: '2026-11-10'
provider_name: TBO.com
provider_slug: tbo
slug: tbo-eligibility
source_date: '2026-11-10'
source_filename: tbo-eligibility.yml
source_heading: Eligibility
source_page: https://www.tbo.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TBO.com\naid: tbo\nurl: https://www.tbo.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The products and services displayed on the Site may not be available for purchase in your particular country\n    or locality.\nentity_types:\n- type: business\n  text: We offer travel agents hotels, flight bookings and travel services purchased from Us.\nrestricted_uses:\n- summary: Sanctioned parties\n  text: neither You nor your stakeholders or directors, or Ultimate Beneficial Owners are on the Office of Foreign\n    Assets Control (OFAC), Specially Designated Nationals\
  \ (SDN), Office of Financial Sanctions Implementation (OFSI)\n    European Union (EU) United Nations (UN) or Blocked Persons list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tbo/eligibility/tbo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from TBO.com's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Distribution
- B2B
- Platform
---
