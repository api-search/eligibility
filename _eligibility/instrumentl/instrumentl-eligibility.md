---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Instrumentl contracts with individual users who use the Services to benefit their own personal research.
    type: individual
  minimum_age:
    text: You represent and warrant that you are of legal age to form a binding contract
    value: legal age
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access specific grant matches, you will be required to sign up for an account, and select a password and user name
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Instrumentl
provenance_date: '2026-11-09'
provider_name: Instrumentl
provider_slug: instrumentl
slug: instrumentl-eligibility
source_date: '2026-11-09'
source_filename: instrumentl-eligibility.yml
source_heading: Eligibility
source_page: https://www.instrumentl.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Instrumentl\naid: instrumentl\nurl: https://www.instrumentl.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Instrumentl contracts with individual users who use the Services to benefit their own personal research.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access specific grant matches, you will be required to sign up for an account, and select a\n    password and user name\nminimum_age:\n  value: legal age\n  text: You represent and warrant that you\
  \ are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/instrumentl/eligibility/instrumentl-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Instrumentl's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Grants
- Non-Profit
- Fundraising
- Grant Management
- Foundation Data
- Philanthropy
- MCP
---
