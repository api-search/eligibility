---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is controlled and/or operated from the United States, and is not intended to subject us to non-U.S. jurisdiction or laws
  entity_types:
  - text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO INITIATE A TRANSACTION.
    type: individual
  - text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE SITE ON BEHALF OF, OR FOR THE BENEFIT OF, ANY CORPORATION, PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED
    type: business
  minimum_age:
    text: BY USING THE SITE, YOU AFFIRM THAT YOU ARE AT LEAST 13 YEARS OF AGE AND OF LEGAL AGE TO ENTER INTO THIS AGREEMENT.
    value: '13'
  restricted_uses:
  - summary: Commercial use of App and Products
    text: solely for your personal, non-commercial use
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
name: Curb
provenance_date: '2026-11-09'
provider_name: Curb
provider_slug: curb
slug: curb-eligibility
source_date: '2026-11-09'
source_filename: curb-eligibility.yml
source_heading: Eligibility
source_page: https://www.curb.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Curb\naid: curb\nurl: https://www.curb.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Site is controlled and/or operated from the United States, and is not intended to subject us to non-U.S.\n    jurisdiction or laws\nentity_types:\n- type: individual\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO INITIATE A TRANSACTION.\n- type: business\n  text: IF YOU ARE AN INDIVIDUAL ACCESSING OR USING THE SITE ON BEHALF OF, OR FOR THE BENEFIT OF, ANY CORPORATION,\n    PARTNERSHIP OR OTHER ENTITY WITH WHICH YOU ARE ASSOCIATED\nrestricted_uses:\n- summary: Commercial\
  \ use of App and Products\n  text: solely for your personal, non-commercial use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: BY USING THE SITE, YOU AFFIRM THAT YOU ARE AT LEAST 13 YEARS OF AGE AND OF LEGAL AGE TO ENTER INTO THIS\n    AGREEMENT.\n"
source_yaml_url: https://artifacts.apis.io/curb/eligibility/curb-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Curb's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Entertainment
- Record Labels
- Media
---
