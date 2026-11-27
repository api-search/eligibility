---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Terms of Service on behalf of a company, business or other legal entity, you represent that you have the authority to bind such entity to this Terms of Service
    type: business
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering. In addition, if you are under 18 years old, you may use the Service, with or without registering, only with the approval of your parent or guardian.
    value: '13'
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
name: Defined Networking
provenance_date: '2026-11-09'
provider_name: Defined Networking
provider_slug: defined-networking
slug: defined-networking-eligibility
source_date: '2026-11-09'
source_filename: defined-networking-eligibility.yml
source_heading: Eligibility
source_page: https://www.defined.net/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Defined Networking\naid: defined-networking\nurl: https://www.defined.net/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Terms of Service on behalf of a company, business or other legal entity, you\n    represent that you have the authority to bind such entity to this Terms of Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service,\
  \ with or without registering.\n    In addition, if you are under 18 years old, you may use the Service, with or without registering, only with\n    the approval of your parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/defined-networking/eligibility/defined-networking-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Defined Networking's own page on 2026-11-09.
synthetic: false
tags:
- Remote Access
- Encryption
- Multi-Cloud
- IoT
- NAT Traversal
- Identity
- Managed networking
---
