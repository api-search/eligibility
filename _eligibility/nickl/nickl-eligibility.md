---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or entities whose subscription(s) or accounts you are accessing the Services as a representative of, if any (collectively, the “Enterprise”)
    type: business
  minimum_age:
    text: You represent that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Services for own use only
    text: the Services are offered only for your use, and not for the use or benefit of any third party.
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
name: NICKL
provenance_date: '2026-11-10'
provider_name: NICKL
provider_slug: nickl
slug: nickl-eligibility
source_date: '2026-11-10'
source_filename: nickl-eligibility.yml
source_heading: Eligibility
source_page: https://www.nicklpass.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NICKL\naid: nickl\nurl: https://www.nicklpass.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity or entities whose subscription(s) or accounts you are accessing the Services as a representative\n    of, if any (collectively, the “Enterprise”)\nrestricted_uses:\n- summary: Services for own use only\n  text: the Services are offered only for your use, and not for the use or benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: You represent that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/nickl/eligibility/nickl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from NICKL's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Subscription Management
- SaaS Management
- Procurement
- Usage Intelligence
- Governance
- Identity
- Spend Management
---
