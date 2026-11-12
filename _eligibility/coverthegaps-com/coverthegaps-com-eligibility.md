---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create an account or use the Service.
    type: individual
  - text: 'Organization/School accounts: the entity represents it has the authority to bind itself and its users to these Terms.'
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account or use the Service.
    value: '18'
  restricted_uses:
  - summary: Arbitration and class waiver for U.S. users
    text: MANDATORY BINDING ARBITRATION AND CLASS ACTION WAIVER FOR U.S. USERS (SEE SECTION 16).
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
name: CoverTheGaps
provenance_date: '2026-11-09'
provider_name: CoverTheGaps
provider_slug: coverthegaps-com
slug: coverthegaps-com-eligibility
source_date: '2026-11-09'
source_filename: coverthegaps-com-eligibility.yml
source_heading: Eligibility
source_page: https://coverthegaps.com/documents/4/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoverTheGaps\naid: coverthegaps-com\nurl: https://coverthegaps.com/documents/4/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create an account or use the Service.\n- type: business\n  text: 'Organization/School accounts: the entity represents it has the authority to bind itself and its users to\n    these Terms.'\nrestricted_uses:\n- summary: Arbitration and class waiver for U.S. users\n  text: MANDATORY BINDING ARBITRATION AND CLASS ACTION WAIVER FOR U.S. USERS (SEE SECTION 16).\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/coverthegaps-com/eligibility/coverthegaps-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CoverTheGaps's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- Language Learning
- English Teaching
- Tutoring
- Homework
- MCP
- AI Assistants
---
