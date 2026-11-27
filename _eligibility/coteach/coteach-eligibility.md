---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access from territories where the contents of the Platform may be illegal is prohibited.
  entity_types:
  - text: you, the user of this website
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: use the Platform to engage in any unlawful, fraudulent, or criminal activity, or for any purpose prohibited by applicable law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Services, you may need to register for an account which will require submission of certain information which may include your name, phone number, email address, or other contact details.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CoTeach
provenance_date: '2026-11-09'
provider_name: CoTeach
provider_slug: coteach
slug: coteach-eligibility
source_date: '2026-11-09'
source_filename: coteach-eligibility.yml
source_heading: Eligibility
source_page: https://www.coteach.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoTeach\naid: coteach\nurl: https://www.coteach.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access from territories where the contents of the Platform may be illegal is prohibited.\nentity_types:\n- type: individual\n  text: you, the user of this website\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: use the Platform to engage in any unlawful, fraudulent, or criminal activity, or for any purpose prohibited\n    by applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Services, you may need to register\
  \ for an account which will require submission of certain information\n    which may include your name, phone number, email address, or other contact details.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coteach/eligibility/coteach-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from CoTeach's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Mathematics
- K-12
- Teachers
- Curriculum
- Lesson Planning
- AI Assistant
- Illustrative Mathematics
- MCP
---
