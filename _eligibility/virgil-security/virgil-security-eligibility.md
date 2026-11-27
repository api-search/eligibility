---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Accessing our services from places where doing so is illegal is strictly prohibited.
  entity_types:
  - text: You represent that you are (a) of legal age to form a binding contract, and (b) legally permitted to use the Services.
    type: individual
  - text: you have the authority to enter into these terms of use personally or on behalf of the entity you have named as the user
    type: business
  minimum_age:
    text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH VIRGIL (A MINIMUM OF 18 YEARS OLD)
    value: '18'
  restricted_uses:
  - summary: No sharing of account access
    text: Users may not share their sign-on credentials or otherwise provide anyone else with access to the Services
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
name: Virgil Security
provenance_date: '2026-11-10'
provider_name: Virgil Security
provider_slug: virgil-security
slug: virgil-security-eligibility
source_date: '2026-11-10'
source_filename: virgil-security-eligibility.yml
source_heading: Eligibility
source_page: https://virgilsecurity.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Virgil Security\naid: virgil-security\nurl: https://virgilsecurity.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Accessing our services from places where doing so is illegal is strictly prohibited.\nentity_types:\n- type: individual\n  text: You represent that you are (a) of legal age to form a binding contract, and (b) legally permitted to use\n    the Services.\n- type: business\n  text: you have the authority to enter into these terms of use personally or on behalf of the entity you have named\n    as the user\nrestricted_uses:\n- summary: No sharing of\
  \ account access\n  text: Users may not share their sign-on credentials or otherwise provide anyone else with access to the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT WITH VIRGIL (A MINIMUM OF 18 YEARS OLD)\n"
source_yaml_url: https://artifacts.apis.io/virgil-security/eligibility/virgil-security-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Virgil Security's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Encryption
- End-to-End Encryption
- Cryptography
- Key Management
- Authentication
- Passwords
- IoT Security
- Developer Tools
---
