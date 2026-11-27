---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Website may not be legal by certain persons or in certain countries. If you access the Website from outside the United States, you do so on your own initiative and are responsible for compliance with local laws.
  entity_types:
  - text: This Website is offered and available to users who are 13 years of age or older.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: No export to embargoed countries or sanctioned persons
    text: No software from this Website may be downloaded or exported (i) into, or to a national or resident of, any country to which the United States has embargoed goods; or (ii) by, or to, anyone on the United States Treasury Department’s list of Specially Designated Nationals
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
name: Tradeweb
provenance_date: '2026-11-10'
provider_name: Tradeweb
provider_slug: tradeweb
slug: tradeweb-eligibility
source_date: '2026-11-10'
source_filename: tradeweb-eligibility.yml
source_heading: Eligibility
source_page: https://www.tradeweb.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tradeweb\naid: tradeweb\nurl: https://www.tradeweb.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Website may not be legal by certain persons or in certain countries. If you access the Website\n    from outside the United States, you do so on your own initiative and are responsible for compliance with local\n    laws.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 13 years of age or older.\nrestricted_uses:\n- summary: No export to embargoed countries or sanctioned persons\n  text: No software from\
  \ this Website may be downloaded or exported (i) into, or to a national or resident of, any\n    country to which the United States has embargoed goods; or (ii) by, or to, anyone on the United States Treasury\n    Department’s list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Website is offered and available to users who are 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/tradeweb/eligibility/tradeweb-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tradeweb's own page on 2026-11-10.
synthetic: false
tags:
- Electronic Trading
- Financial Markets
- Fixed Income
- Market Data
- OTC Trading
---
