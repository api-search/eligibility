---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 13 years or older and are not barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you are 13 years or older and are not barred from using the Services under applicable law.
    value: '13'
  restricted_uses:
  - summary: No commercial use
    text: Use the Services for any revenue generating endeavor, commercial enterprise or other purpose for which it is not designed or intended
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: YOU UNDERSTAND THAT SEATED DOES NOT SCREEN OR INQUIRE INTO THE BACKGROUND OF ANY USERS OF THE SERVICES, NOR DOES SEATED MAKE ANY ATTEMPT TO VERIFY THE STATEMENTS OF USERS OF THE SERVICES.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Seated
provenance_date: '2026-11-10'
provider_name: Seated
provider_slug: seated
slug: seated-eligibility
source_date: '2026-11-10'
source_filename: seated-eligibility.yml
source_heading: Eligibility
source_page: https://support.seated.com/en/articles/13944961-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seated\naid: seated\nurl: https://support.seated.com/en/articles/13944961-terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 13 years or older and are not barred from using the Services under\n    applicable law.\nrestricted_uses:\n- summary: No commercial use\n  text: Use the Services for any revenue generating endeavor, commercial enterprise or other purpose for which it\n    is not designed or intended\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ YOU UNDERSTAND THAT SEATED DOES NOT SCREEN OR INQUIRE INTO THE BACKGROUND OF ANY USERS OF THE SERVICES,\n    NOR DOES SEATED MAKE ANY ATTEMPT TO VERIFY THE STATEMENTS OF USERS OF THE SERVICES.\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are 13 years or older and are not barred from using the Services under\n    applicable law.\n"
source_yaml_url: https://artifacts.apis.io/seated/eligibility/seated-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Seated's own page on 2026-11-10.
synthetic: false
tags:
- Live Events
- Concerts
- Ticketing
- Artists
- Venues
- tour dates
- fan notifications
- Presales
- Music
- Entertainment
---
