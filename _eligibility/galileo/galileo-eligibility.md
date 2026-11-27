---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within the United States where the Services are available. Services are not available to users located outside the United States.
  entity_types:
  - text: The Site and Services are only for users of the age of 18.
    type: individual
  minimum_age:
    text: The Site and Services are only for users of the age of 18.
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: The Site is not intended for use in the event of an emergency or other urgent situations.
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
name: Galileo
provenance_date: '2026-11-09'
provider_name: Galileo
provider_slug: galileo
slug: galileo-eligibility
source_date: '2026-11-09'
source_filename: galileo-eligibility.yml
source_heading: Eligibility
source_page: https://galileo.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Galileo\naid: galileo\nurl: https://galileo.io/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Site and/or the Services is limited exclusively to users located in States within\n    the United States where the Services are available. Services are not available to users located outside the\n    United States.\nentity_types:\n- type: individual\n  text: The Site and Services are only for users of the age of 18.\nrestricted_uses:\n- summary: Not for emergencies\n  text: The Site is not intended for use in the event of an emergency or\
  \ other urgent situations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and Services are only for users of the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/galileo/eligibility/galileo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Galileo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Digital Health
- Primary Care
- Multi-Specialty Care
- Value-Based Care
- Virtual Care
- Health Plans
- Employer Health
- Platform
---
