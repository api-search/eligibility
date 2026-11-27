---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: developers, project managers, product managers and other technology specialists ("Builders")
    type: individual
  - text: companies that are building certain technology ("Clients")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or infringing content or use
    text: may violate applicable laws or governmental regulations
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: your Account will be subject to verification, including validation against third-party databases or verification of one or more official government or legal documents that confirm your identity, location, and ability to act on behalf of your business.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: A.Team
provenance_date: '2026-11-09'
provider_name: A.Team
provider_slug: ateam
slug: ateam-eligibility
source_date: '2026-11-09'
source_filename: ateam-eligibility.yml
source_heading: Eligibility
source_page: https://www.a.team/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: A.Team\naid: ateam\nurl: https://www.a.team/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: developers, project managers, product managers and other technology specialists (\"Builders\")\n- type: business\n  text: companies that are building certain technology (\"Clients\")\nrestricted_uses:\n- summary: Unlawful or infringing content or use\n  text: may violate applicable laws or governmental regulations\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: your Account will be subject\
  \ to verification, including validation against third-party databases or verification\n    of one or more official government or legal documents that confirm your identity, location, and ability to act\n    on behalf of your business.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ateam/eligibility/ateam-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from A.Team's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Talent Network
- AI Talent
- Staffing
- AI Agents
- Engineering
- Consulting
---
