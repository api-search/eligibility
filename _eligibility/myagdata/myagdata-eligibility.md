---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If a corporation or limited liability company, “You” or “Your” means the corporation or limited liability company and its affiliates, employees, agents, officers, directors, shareholders and members accessing the Services
    type: business
  - text: if not a corporation or limited liability company, “You” or “Your” means the person or user, and his or her partners, agents and employees accessing the Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You shall use the Services for lawful purposes only.
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
name: MyAgData
provenance_date: '2026-11-10'
provider_name: MyAgData
provider_slug: myagdata
slug: myagdata-eligibility
source_date: '2026-11-10'
source_filename: myagdata-eligibility.yml
source_heading: Eligibility
source_page: https://myagdata.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MyAgData\naid: myagdata\nurl: https://myagdata.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If a corporation or limited liability company, “You” or “Your” means the corporation or limited liability\n    company and its affiliates, employees, agents, officers, directors, shareholders and members accessing the Services\n- type: individual\n  text: if not a corporation or limited liability company, “You” or “Your” means the person or user, and his or\n    her partners, agents and employees accessing the Services.\nrestricted_uses:\n\
  - summary: Lawful use only\n  text: You shall use the Services for lawful purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/myagdata/eligibility/myagdata-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from MyAgData's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agriculture
- USDA
- Reporting
- Data
- Technology
---
