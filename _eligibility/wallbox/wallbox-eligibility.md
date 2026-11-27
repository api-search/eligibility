---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - ES
    - DE
    - AT
    - BE
    - DK
    - FR
    - IT
    - LU
    - 'NO'
    - NL
    - PT
    - GB
    text: 'WALLBOX ships Products in the following territories: Spain, Germany, Austria, Belgium, Denmark, France, Italy, Luxembourg, Norway, the Netherlands, Portugal, United Kingdom, as well as in any other countries that WALLBOX may establish.'
  entity_types:
  - text: Sales are aimed exclusively at Users over 16 years old with full capacity to enter into an agreement.
    type: individual
  - text: any natural or legal person who uses the Service
    type: business
  minimum_age:
    text: Sales are aimed exclusively at Users over 16 years old with full capacity to enter into an agreement.
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful use
    text: Clients undertake to not use the Charging Service for illegal purposes that are contrary to the provisions of the General Terms and Conditions, detrimental to the rights and interests of WALLBOX or third parties
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
name: Wallbox
provenance_date: '2026-11-10'
provider_name: Wallbox
provider_slug: wallbox
slug: wallbox-eligibility
source_date: '2026-11-10'
source_filename: wallbox-eligibility.yml
source_heading: Eligibility
source_page: https://support.wallbox.com/en/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wallbox\naid: wallbox\nurl: https://support.wallbox.com/en/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - ES\n  - DE\n  - AT\n  - BE\n  - DK\n  - FR\n  - IT\n  - LU\n  - 'NO'\n  - NL\n  - PT\n  - GB\n  excluded: []\n  text: 'WALLBOX ships Products in the following territories: Spain, Germany, Austria, Belgium, Denmark, France,\n    Italy, Luxembourg, Norway, the Netherlands, Portugal, United Kingdom, as well as in any other countries that\n    WALLBOX may establish.'\nentity_types:\n- type: individual\n  text: Sales are aimed exclusively at Users over 16 years old with full capacity to enter\
  \ into an agreement.\n- type: business\n  text: any natural or legal person who uses the Service\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: Clients undertake to not use the Charging Service for illegal purposes that are contrary to the provisions\n    of the General Terms and Conditions, detrimental to the rights and interests of WALLBOX or third parties\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Sales are aimed exclusively at Users over 16 years old with full capacity to enter into an agreement.\n"
source_yaml_url: https://artifacts.apis.io/wallbox/eligibility/wallbox-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Wallbox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EV Charging
- Smart Hardware
- Energy Management
- Software-as-a-Service
---
