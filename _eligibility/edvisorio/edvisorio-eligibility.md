---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this TOS on behalf of a company or other legal entity, you affirm that you have the authority to bind such entity and its affiliates to these TOS.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful use
    text: (c) use the Service in any unlawful manner or in any manner that interferes with or disrupts the integrity or performance of the Service and its components.
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
name: Edvisor.io
provenance_date: '2026-11-09'
provider_name: Edvisor.io
provider_slug: edvisorio
slug: edvisorio-eligibility
source_date: '2026-11-09'
source_filename: edvisorio-eligibility.yml
source_heading: Eligibility
source_page: https://edvisor.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Edvisor.io\naid: edvisorio\nurl: https://edvisor.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this TOS on behalf of a company or other legal entity, you affirm that you have\n    the authority to bind such entity and its affiliates to these TOS.\nrestricted_uses:\n- summary: No unlawful use\n  text: (c) use the Service in any unlawful manner or in any manner that interferes with or disrupts the integrity\n    or performance of the Service and its components.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/edvisorio/eligibility/edvisorio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Edvisor.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Student Recruitment
- International Education
- EdTech
- GraphQL
- Marketplace
- Webhook
---
