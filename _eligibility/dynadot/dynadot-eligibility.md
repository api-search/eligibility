---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Part I (Service Agreement) applies to any person or entity which creates a user account with Dynadot
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: objectionable or illegal activity
    text: where such Service or account is used in connection with a morally objectionable activity, including but not limited to spam, fraud, illegal activity
  - summary: sanctioned persons
    text: You represent that You are not (a) directly or indirectly owned or controlled by any Person currently included on the Specially Designated Nationals and Blocked Persons List
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
name: Dynadot
provenance_date: '2026-11-09'
provider_name: Dynadot
provider_slug: dynadot
slug: dynadot-eligibility
source_date: '2026-11-09'
source_filename: dynadot-eligibility.yml
source_heading: Eligibility
source_page: https://www.dynadot.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dynadot\naid: dynadot\nurl: https://www.dynadot.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: This Part I (Service Agreement) applies to any person or entity which creates a user account with Dynadot\nrestricted_uses:\n- summary: objectionable or illegal activity\n  text: where such Service or account is used in connection with a morally objectionable activity, including but\n    not limited to spam, fraud, illegal activity\n- summary: sanctioned persons\n  text: You represent that You are not (a) directly\
  \ or indirectly owned or controlled by any Person currently included\n    on the Specially Designated Nationals and Blocked Persons List\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dynadot/eligibility/dynadot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Dynadot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Domain Registrar
- Marketplace
- DNS Management
- SSL
---
