---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some services and features may not be available in all countries, in all languages, or in all operating systems.
  entity_types:
  - text: OUR SERVICE IS NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 16.
    type: individual
  minimum_age:
    text: OUR SERVICE IS NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 16.
    value: '16'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: 'You may not access, use, export, re-export, transfer, or otherwise make available the Service, directly or indirectly: (a) into any country or territory subject to comprehensive trade sanctions or embargoes'
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
name: Confide *
provenance_date: '2026-11-09'
provider_name: Confide *
provider_slug: confide
slug: confide-eligibility
source_date: '2026-11-09'
source_filename: confide-eligibility.yml
source_heading: Eligibility
source_page: https://support.bendingspoons.com/tos?app=779883419
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Confide *\naid: confide\nurl: https://support.bendingspoons.com/tos?app=779883419\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Some services and features may not be available in all countries, in all languages, or in all operating\n    systems.\nentity_types:\n- type: individual\n  text: OUR SERVICE IS NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 16.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: 'You may not access, use, export, re-export, transfer, or otherwise make available the Service, directly\n    or indirectly: (a) into any\
  \ country or territory subject to comprehensive trade sanctions or embargoes'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: OUR SERVICE IS NOT AVAILABLE TO INDIVIDUALS UNDER THE AGE OF 16.\n"
source_yaml_url: https://artifacts.apis.io/confide/eligibility/confide-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Confide *'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Messaging
- Encryption
- Privacy
- Security
- Mobile
- Communications
---
