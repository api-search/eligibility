---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only individuals are permitted to register and admitted as users.
    type: individual
  minimum_age:
    text: IF YOU ARE UNDER 13, PLEASE DO NOT SUBMIT ANY PERSONALLY IDENTIFIABLE INFORMATION TO CRYTEK.
    value: null
  restricted_uses:
  - summary: Business or commercial purposes
    text: The use for business or commercial purposes is prohibited.
  - summary: Anonymization services
    text: The use of GFace and CRYTEK Services through an anonymization service that is hiding the true IP address of the User is prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To create a CRYTEK Account, you must have an email address and provide truthful and accurate information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Crytek
provenance_date: '2026-11-09'
provider_name: Crytek
provider_slug: crytek
slug: crytek-eligibility
source_date: '2026-11-09'
source_filename: crytek-eligibility.yml
source_heading: Eligibility
source_page: https://www.crytek.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Crytek\naid: crytek\nurl: https://www.crytek.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only individuals are permitted to register and admitted as users.\nrestricted_uses:\n- summary: Business or commercial purposes\n  text: The use for business or commercial purposes is prohibited.\n- summary: Anonymization services\n  text: The use of GFace and CRYTEK Services through an anonymization service that is hiding the true IP address\n    of the User is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: To create a CRYTEK Account, you must have an email address and provide truthful and accurate information.\nminimum_age:\n  value: null\n  text: IF YOU ARE UNDER 13, PLEASE DO NOT SUBMIT ANY PERSONALLY IDENTIFIABLE INFORMATION TO CRYTEK.\n"
source_yaml_url: https://artifacts.apis.io/crytek/eligibility/crytek-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Crytek's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video Games
- Game Development
- CryEngine
- Gaming
---
