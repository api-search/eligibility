---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Client" refers to businesses and enterprises using our Service.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited product categories
    text: 'Users are prohibited from using our Service to procure, ship, or handle: a) Illegal substances b) Controlled substances without proper authorization (excluding over-the-counter medications) c) Firearms and weapons'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Full access to our Platform requires execution of a Master Logistics & Software License Agreement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tenkara
provenance_date: '2026-11-10'
provider_name: Tenkara
provider_slug: tenkara
slug: tenkara-eligibility
source_date: '2026-11-10'
source_filename: tenkara-eligibility.yml
source_heading: Eligibility
source_page: https://tenkara.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tenkara\naid: tenkara\nurl: https://tenkara.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: '\"Client\" refers to businesses and enterprises using our Service.'\nrestricted_uses:\n- summary: Prohibited product categories\n  text: 'Users are prohibited from using our Service to procure, ship, or handle: a) Illegal substances b) Controlled\n    substances without proper authorization (excluding over-the-counter medications) c) Firearms and weapons'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n\
  \  text: Full access to our Platform requires execution of a Master Logistics & Software License Agreement.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tenkara/eligibility/tenkara-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Tenkara's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Manufacturing
- Supply Chain
- Procurement
- Logistics
- Compliance
---
