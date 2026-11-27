---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are a resident of a country embargoed by the United States
  entity_types:
  - text: you may access and use the Services for your own professional and business purposes
    type: business
  minimum_age:
    text: Any use or access to the Services by anyone under 18 is strictly prohibited
    value: '18'
  restricted_uses:
  - summary: No personal or household use
    text: The Services are not available for personal, family or household uses.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: access the online bidding engine to bid online in real time at our auctions or in other sale events (after requesting bidding privileges and being approved)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: IronPlanet
provenance_date: '2026-11-09'
provider_name: IronPlanet
provider_slug: ironplanet
slug: ironplanet-eligibility
source_date: '2026-11-09'
source_filename: ironplanet-eligibility.yml
source_heading: Eligibility
source_page: https://www.ironplanet.com/pop/terms_page.jsp?noh1=yes
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IronPlanet\naid: ironplanet\nurl: https://www.ironplanet.com/pop/terms_page.jsp?noh1=yes\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are a resident of a country embargoed by the United States\nentity_types:\n- type: business\n  text: you may access and use the Services for your own professional and business purposes\nrestricted_uses:\n- summary: No personal or household use\n  text: The Services are not available for personal, family or household uses.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n\
  \  text: access the online bidding engine to bid online in real time at our auctions or in other sale events (after\n    requesting bidding privileges and being approved)\nminimum_age:\n  value: '18'\n  text: Any use or access to the Services by anyone under 18 is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/ironplanet/eligibility/ironplanet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from IronPlanet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Heavy Equipment
- Auctions
- Used Equipment
- Construction
- Ritchie Bros
---
