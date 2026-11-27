---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AT
    - BE
    - DK
    - FR
    - DE
    - IT
    - LU
    - NL
    - ES
    - SE
    - GB
    text: Cowboy delivers new bikes exclusively to Austria, Belgium, Denmark, France, Germany, Italy, Luxembourg, the Netherlands, Spain, Sweden, and the United Kingdom.
  entity_types:
  - text: To be able to place an order, you must be above the age of 18 and not legally incapacitated and have a valid e-mail address.
    type: individual
  - text: Any natural or legal person with whom Cowboy enters into an agreement or with whom Cowboy is negotiating about the conclusion of the agreement.
    type: business
  minimum_age:
    text: To be able to place an order, you must be above the age of 18 and not legally incapacitated
    value: '18'
  restricted_uses:
  - summary: Non-commercial website use only
    text: we grant you a non-exclusive, non-transferable, limited and revocable right of use of the website for non-commercial purposes
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
name: Cowboy
provenance_date: '2026-11-09'
provider_name: Cowboy
provider_slug: cowboy
slug: cowboy-eligibility
source_date: '2026-11-09'
source_filename: cowboy-eligibility.yml
source_heading: Eligibility
source_page: https://cowboy.com/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cowboy\naid: cowboy\nurl: https://cowboy.com/pages/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AT\n  - BE\n  - DK\n  - FR\n  - DE\n  - IT\n  - LU\n  - NL\n  - ES\n  - SE\n  - GB\n  excluded: []\n  text: Cowboy delivers new bikes exclusively to Austria, Belgium, Denmark, France, Germany, Italy, Luxembourg,\n    the Netherlands, Spain, Sweden, and the United Kingdom.\nentity_types:\n- type: individual\n  text: To be able to place an order, you must be above the age of 18 and not legally incapacitated and have a valid\n    e-mail address.\n- type: business\n  text: Any natural or legal person\
  \ with whom Cowboy enters into an agreement or with whom Cowboy is negotiating\n    about the conclusion of the agreement.\nrestricted_uses:\n- summary: Non-commercial website use only\n  text: we grant you a non-exclusive, non-transferable, limited and revocable right of use of the website for non-commercial\n    purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To be able to place an order, you must be above the age of 18 and not legally incapacitated\n"
source_yaml_url: https://artifacts.apis.io/cowboy/eligibility/cowboy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Cowboy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mobility
- Electric Bikes
- Micromobility
- Connected Devices
- Consumer Hardware
- Transportation
---
