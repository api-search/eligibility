---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 13 years of age, you are not authorized to use the Service. In addition, if you are under 18 years old, you may use the Service only with the approval of your parent or guardian.
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service.
    value: '13'
  restricted_uses:
  - summary: Export controls
    text: Software available in connection with the Service and the transmission of applicable data, if any, is subject to United States export controls.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You are required to register with HiHello in order to access and use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: HiHello
provenance_date: '2026-11-09'
provider_name: HiHello
provider_slug: hihello
slug: hihello-eligibility
source_date: '2026-11-09'
source_filename: hihello-eligibility.yml
source_heading: Eligibility
source_page: https://www.hihello.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HiHello\naid: hihello\nurl: https://www.hihello.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 13 years of age, you are not authorized to use the Service. In addition, if you are under\n    18 years old, you may use the Service only with the approval of your parent or guardian.\nrestricted_uses:\n- summary: Export controls\n  text: Software available in connection with the Service and the transmission of applicable data, if any, is subject\n    to United States export controls.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: You are required to register with HiHello in order to access and use the Service.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/hihello/eligibility/hihello-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from HiHello's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Digital Business Cards
- Contact Management
- Networking
- Professional Presence
- CRM Integration
- Enterprise
---
