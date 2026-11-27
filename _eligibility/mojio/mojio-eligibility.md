---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You will only use the Mojio Solution in jurisdictions where the Mojio Solution may lawfully be used.
  entity_types:
  - text: YOU HAVE REACHED THE AGE OF MAJORITY IN YOUR JURISDICTION, (II) YOU HAVE THE CAPACITY TO ENTER INTO BINDING OBLIGATIONS
    type: individual
  - text: IF YOU ARE USING THE MOJIO SOLUTION ON BEHALF OF ANOTHER PERSON OR A CORPORATE ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE THE AUTHORITY TO BIND SUCH PERSON OR ENTITY TO THESE TERMS OF USE.
    type: business
  minimum_age:
    text: YOU HAVE REACHED THE AGE OF MAJORITY IN YOUR JURISDICTION
    value: age of majority in jurisdiction
  restricted_uses:
  - summary: Limited purposes without permission
    text: 'You will not, without our prior written permission, use the Mojio Solution for any purpose other than to: (a) discover and learn about connected-car products and services offered by us'
  - summary: Sanctioned countries (Apple App Store)
    text: 'You represent and warrant that you are not: (i) located in any country that is subject to a U.S. Government embargo'
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
name: Moj.io
provenance_date: '2026-11-10'
provider_name: Moj.io
provider_slug: mojio
slug: mojio-eligibility
source_date: '2026-11-10'
source_filename: mojio-eligibility.yml
source_heading: Eligibility
source_page: https://www.moj.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moj.io\naid: mojio\nurl: https://www.moj.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You will only use the Mojio Solution in jurisdictions where the Mojio Solution may lawfully be used.\nentity_types:\n- type: individual\n  text: YOU HAVE REACHED THE AGE OF MAJORITY IN YOUR JURISDICTION, (II) YOU HAVE THE CAPACITY TO ENTER INTO BINDING\n    OBLIGATIONS\n- type: business\n  text: IF YOU ARE USING THE MOJIO SOLUTION ON BEHALF OF ANOTHER PERSON OR A CORPORATE ENTITY, YOU REPRESENT AND\n    WARRANT THAT YOU HAVE THE AUTHORITY TO BIND SUCH PERSON OR ENTITY TO THESE TERMS\
  \ OF USE.\nrestricted_uses:\n- summary: Limited purposes without permission\n  text: 'You will not, without our prior written permission, use the Mojio Solution for any purpose other than to:\n    (a) discover and learn about connected-car products and services offered by us'\n- summary: Sanctioned countries (Apple App Store)\n  text: 'You represent and warrant that you are not: (i) located in any country that is subject to a U.S. Government\n    embargo'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in jurisdiction\n  text: YOU HAVE REACHED THE AGE OF MAJORITY IN YOUR JURISDICTION\n"
source_yaml_url: https://artifacts.apis.io/mojio/eligibility/mojio-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Moj.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Connected Vehicles
- Telematics
- Mobility
- Automotive
- Fleet Management
- Vehicle Data
- IoT
---
