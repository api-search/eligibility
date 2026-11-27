---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You shall not use the Service if you are located in a country embargoed by the United States or if you are on the U.S. Treasury Department's list of Specially Designated Nationals.
  entity_types:
  - text: Independent Artist Plans if you are an Artist
    type: individual
  - text: (ii) Enterprise Plans if you are a merchandise company, record label or similar organization.
    type: business
  minimum_age:
    text: You shall not create an Account or access the Service if you are under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Non-commercial account use
    text: You shall use your Account only for non-commercial purposes.
  - summary: Embargoed countries
    text: You shall not use the Service if you are located in a country embargoed by the United States
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information applicable to a purchase may be required prior to our acceptance of any order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Merchbar
provenance_date: '2026-11-10'
provider_name: Merchbar
provider_slug: merchbar
slug: merchbar-eligibility
source_date: '2026-11-10'
source_filename: merchbar-eligibility.yml
source_heading: Eligibility
source_page: https://help.merchbar.com/hc/en-us/articles/360044115794-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Merchbar\naid: merchbar\nurl: https://help.merchbar.com/hc/en-us/articles/360044115794-Terms-of-Service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You shall not use the Service if you are located in a country embargoed by the United States or if you are\n    on the U.S. Treasury Department's list of Specially Designated Nationals.\nentity_types:\n- type: individual\n  text: Independent Artist Plans if you are an Artist\n- type: business\n  text: (ii) Enterprise Plans if you are a merchandise company, record label or similar organization.\nrestricted_uses:\n\
  - summary: Non-commercial account use\n  text: You shall use your Account only for non-commercial purposes.\n- summary: Embargoed countries\n  text: You shall not use the Service if you are located in a country embargoed by the United States\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information applicable to a purchase may be required prior to our acceptance of any order.\nminimum_age:\n  value: '13'\n  text: You shall not create an Account or access the Service if you are under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/merchbar/eligibility/merchbar-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Merchbar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Music
- Merchandise
- E-Commerce
- Retail
- Vinyl
- Consumer
---
