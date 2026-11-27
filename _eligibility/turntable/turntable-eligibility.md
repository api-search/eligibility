---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Service is offered only within the United States. We do not intentionally offer or make the Service available to residents of the European Union, the United Kingdom, or any other jurisdiction outside the United States.
  entity_types:
  - text: You must be at least 13 years old to use the Service. If you are 13 to 17 years old, you may use the Service only with the consent and supervision of a parent or legal guardian.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Sanctioned parties
    text: you are not located in a country that is subject to a U.S. Government embargo
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
name: turntable
provenance_date: '2026-11-10'
provider_name: turntable
provider_slug: turntable
slug: turntable-eligibility
source_date: '2026-11-10'
source_filename: turntable-eligibility.yml
source_heading: Eligibility
source_page: https://hangout.fm/terms-and-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: turntable\naid: turntable\nurl: https://hangout.fm/terms-and-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Service is offered only within the United States. We do not intentionally offer or make the Service\n    available to residents of the European Union, the United Kingdom, or any other jurisdiction outside the United\n    States.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service. If you are 13 to 17 years old, you may use the Service\n    only with the consent and supervision of a parent or legal guardian.\nrestricted_uses:\n\
  - summary: Sanctioned parties\n  text: you are not located in a country that is subject to a U.S. Government embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/turntable/eligibility/turntable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from turntable's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Music
- Social
- Streaming
- Entertainment
- Consumer
- Media
---
