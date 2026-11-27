---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are for consumers only – they are only to be used for non-commercial, non-business, private purposes.
    type: individual
  - text: The Services are for consumers only – they are only to be used for non-commercial, non-business, private purposes.
    type: business
  minimum_age:
    text: No one under the age of 13 is allowed to create an account or use the Services.
    value: '13'
  restricted_uses:
  - summary: Commercial use prohibited
    text: (f) any loss resulting from the use of the Services for commercial purposes.
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
name: Lapse
provenance_date: '2026-11-09'
provider_name: Lapse
provider_slug: lapse
slug: lapse-eligibility
source_date: '2026-11-09'
source_filename: lapse-eligibility.yml
source_heading: Eligibility
source_page: https://lapse.com/pdf/Lapse%20-%20Terms%20of%20Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lapse\naid: lapse\nurl: https://lapse.com/pdf/Lapse%20-%20Terms%20of%20Service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are for consumers only – they are only to be used for non-commercial, non-business, private\n    purposes.\n- type: business\n  text: The Services are for consumers only – they are only to be used for non-commercial, non-business, private\n    purposes.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: (f) any loss resulting from the use of the Services for commercial purposes.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: No one under the age of 13 is allowed to create an account or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/lapse/eligibility/lapse-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lapse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Photography
- Photo Sharing
- Social
- Mobile
- iOS
- Camera
---
