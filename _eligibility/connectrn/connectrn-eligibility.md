---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: connectRN grants to Customer ... a limited, revocable, nontransferable, and nonexclusive right to permit Authorized Users to use the Platform in the United States
  entity_types:
  - text: the entity or facility that is named on the Order Form (as defined below) (the “Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business use only
    text: solely in connection with the Services, all solely for Customer’s own internal business operations
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
name: ConnectRN
provenance_date: '2026-11-09'
provider_name: ConnectRN
provider_slug: connectrn
slug: connectrn-eligibility
source_date: '2026-11-09'
source_filename: connectrn-eligibility.yml
source_heading: Eligibility
source_page: https://www.connectrn.com/main-services-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConnectRN\naid: connectrn\nurl: https://www.connectrn.com/main-services-agreement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: connectRN grants to Customer ... a limited, revocable, nontransferable, and nonexclusive right to permit\n    Authorized Users to use the Platform in the United States\nentity_types:\n- type: business\n  text: the entity or facility that is named on the Order Form (as defined below) (the “Customer”)\nrestricted_uses:\n- summary: Internal business use only\n  text: solely in connection with the Services, all solely for Customer’s own internal business\
  \ operations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/connectrn/eligibility/connectrn-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ConnectRN's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Health IT
- Staffing
- Nursing
- Workforce Management
- Marketplace
- Mobile App
---
