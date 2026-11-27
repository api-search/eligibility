---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use the Services in a country that is subject to a U.S. Government embargo or subject toUnited Nations Security Council Sanctions
  entity_types:
  - text: IF YOU ARE AN INDIVIDUAL ACCESSING ANY OF THE NEXON API SERVICES ON BEHALF OF AN ENTITY, YOU ACKNOWLEDGE AND AGREE THAT YOU HAVE THE AUTHORITY TO ACCEPT THESE NEXON API TERMS ON BEHALF OF SUCH ENTITY.
    type: individual
  - text: If You are using the Nexon API Services on behalf of someone else (such as Your employer), You represent and warrant that You have authority to bind that person or entity to the Nexon API Terms
    type: business
  minimum_age:
    text: REPRESENT THAT YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT
    value: null
  restricted_uses:
  - summary: No apps for children under 13
    text: Applications should not be designed for nor marketed to users under the age of 13 years of age.
  - summary: No use for sanctioned parties
    text: Use the services if you are on any U.S. Government list of prohibited or restricted parties.
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
name: Nexon
provenance_date: '2026-11-10'
provider_name: Nexon
provider_slug: nexon-inc
slug: nexon-inc-eligibility
source_date: '2026-11-10'
source_filename: nexon-inc-eligibility.yml
source_heading: Eligibility
source_page: https://openapi.nexon.com/support/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nexon\naid: nexon-inc\nurl: https://openapi.nexon.com/support/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use the Services in a country that is subject to a U.S. Government embargo or subject toUnited Nations Security\n    Council Sanctions\nentity_types:\n- type: individual\n  text: IF YOU ARE AN INDIVIDUAL ACCESSING ANY OF THE NEXON API SERVICES ON BEHALF OF AN ENTITY, YOU ACKNOWLEDGE\n    AND AGREE THAT YOU HAVE THE AUTHORITY TO ACCEPT THESE NEXON API TERMS ON BEHALF OF SUCH ENTITY.\n- type: business\n  text: If You are using the Nexon API Services on behalf of someone\
  \ else (such as Your employer), You represent\n    and warrant that You have authority to bind that person or entity to the Nexon API Terms\nrestricted_uses:\n- summary: No apps for children under 13\n  text: Applications should not be designed for nor marketed to users under the age of 13 years of age.\n- summary: No use for sanctioned parties\n  text: Use the services if you are on any U.S. Government list of prohibited or restricted parties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: REPRESENT THAT YOU ARE OF LEGAL AGE TO FORM A BINDING CONTRACT\n"
source_yaml_url: https://artifacts.apis.io/nexon-inc/eligibility/nexon-inc-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Nexon's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Gaming
- Video Games
- Game Data
- Developer API
- OpenAPI
---
