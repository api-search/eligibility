---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CN
    - HK
    - MO
    served: []
    text: The Services are not authorized for use, and may not be accessed, from within mainland China, Hong Kong, or Macao.
  entity_types:
  - text: If you are entering into these Terms on behalf of a company, news organization, or other legal entity, you represent that you have the authority to bind such entity to these terms.
    type: individual
  minimum_age:
    text: The Services are restricted to the use of persons 13 and older.
    value: '13'
  restricted_uses:
  - summary: Not for sharing access
    text: This access is granted solely to you as an individual professional. You may not share your login credentials, passwords, or access with other members of your newsroom, colleagues, or institution.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CN
- HK
- MO
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WireScreen
provenance_date: '2026-11-10'
provider_name: WireScreen
provider_slug: wirescreen
slug: wirescreen-eligibility
source_date: '2026-11-10'
source_filename: wirescreen-eligibility.yml
source_heading: Eligibility
source_page: https://wirescreen.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WireScreen\naid: wirescreen\nurl: https://wirescreen.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CN\n  - HK\n  - MO\n  text: The Services are not authorized for use, and may not be accessed, from within mainland China, Hong Kong,\n    or Macao.\nentity_types:\n- type: individual\n  text: If you are entering into these Terms on behalf of a company, news organization, or other legal entity, you\n    represent that you have the authority to bind such entity to these terms.\nrestricted_uses:\n- summary: Not for sharing access\n  text: This access is granted solely to\
  \ you as an individual professional. You may not share your login credentials,\n    passwords, or access with other members of your newsroom, colleagues, or institution.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are restricted to the use of persons 13 and older.\n"
source_yaml_url: https://artifacts.apis.io/wirescreen/eligibility/wirescreen-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from WireScreen's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Business
- Intelligence
- China
- Risk Management
- Compliance
---
