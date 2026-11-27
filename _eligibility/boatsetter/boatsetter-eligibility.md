---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended solely for persons who are 18 or older.
    type: individual
  - text: 'When using or opening an account with Boatsetter on behalf of a company, entity, or organization, you represent and warrant that you: (i) are an authorized representative of that entity'
    type: business
  minimum_age:
    text: The Services are intended solely for persons who are 18 or older.
    value: '18'
  restricted_uses:
  - summary: Owners may not offer boats they do not own or have permission to rent
    text: offer, as an Owner, any Boats that you do not yourself own or have permission to rent
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: we do not attempt to confirm, and do not confirm, any Member's purported identity or other information provided by such Member.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Boatsetter
provenance_date: '2026-11-09'
provider_name: Boatsetter
provider_slug: boatsetter
slug: boatsetter-eligibility
source_date: '2026-11-09'
source_filename: boatsetter-eligibility.yml
source_heading: Eligibility
source_page: https://www.boatsetter.com/legal/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boatsetter\naid: boatsetter\nurl: https://www.boatsetter.com/legal/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended solely for persons who are 18 or older.\n- type: business\n  text: 'When using or opening an account with Boatsetter on behalf of a company, entity, or organization, you represent\n    and warrant that you: (i) are an authorized representative of that entity'\nrestricted_uses:\n- summary: Owners may not offer boats they do not own or have permission to rent\n\
  \  text: offer, as an Owner, any Boats that you do not yourself own or have permission to rent\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: we do not attempt to confirm, and do not confirm, any Member's purported identity or other information provided\n    by such Member.\nminimum_age:\n  value: '18'\n  text: The Services are intended solely for persons who are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/boatsetter/eligibility/boatsetter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Boatsetter's own page on 2026-11-09.
synthetic: false
tags:
- Boat Rental
- Peer-to-Peer
- Marketplace
- Travel
- Boating
- Maritime
- Yacht Charter
- Watersports
- Recreation
- Sharing Economy
---
