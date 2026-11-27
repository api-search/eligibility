---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of an entity, that entity is deemed to be the Customer herein
    type: business
  minimum_age:
    text: THE SERVICES ARE NOT INTENDED FOR USERS UNDER THE AGE OF 13
    value: '13'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: 'you are not: (a) located in a country that is subject to a U.S. Government embargo, or designated by the U.S. Government as a ''terrorist supporting'' country; and (b) listed on any U.S. Government list of prohibited or restricted parties'
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
name: Bruno
provenance_date: '2026-11-09'
provider_name: Bruno
provider_slug: bruno-api
slug: bruno-api-eligibility
source_date: '2026-11-09'
source_filename: bruno-api-eligibility.yml
source_heading: Eligibility
source_page: https://www.usebruno.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bruno\naid: bruno-api\nurl: https://www.usebruno.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of an entity, that entity is deemed to be the Customer herein\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: 'you are not: (a) located in a country that is subject to a U.S. Government embargo, or designated by the\n    U.S. Government as a ''terrorist supporting'' country; and (b) listed on any U.S. Government list of prohibited\n    or restricted parties'\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: THE SERVICES ARE NOT INTENDED FOR USERS UNDER THE AGE OF 13\n"
source_yaml_url: https://artifacts.apis.io/bruno-api/eligibility/bruno-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bruno's own page on 2026-11-09.
synthetic: false
tags:
- API Client
- API Testing
- Developer Tools
- Open Source
- Git-Native
- CLI
- Postman Alternative
- A2A
- Testing
---
