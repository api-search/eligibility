---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An attorney admitted to practice in good standing with your respective bar, legal professional in good standing, law student or legal support staff
    type: individual
  - text: A law firm, legal department, law school or business entity that wishes to use Paladin’s Services.
    type: business
  - text: A bar organization, onprofit or legal aid organization that wishes to partner with Paladin to facilitate their pro bono.
    type: nonprofit
  minimum_age:
    text: 18+ years old.
    value: '18'
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
name: Paladin
provenance_date: '2026-11-10'
provider_name: Paladin
provider_slug: paladin
slug: paladin-eligibility
source_date: '2026-11-10'
source_filename: paladin-eligibility.yml
source_heading: Eligibility
source_page: https://www.joinpaladin.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paladin\naid: paladin\nurl: https://www.joinpaladin.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An attorney admitted to practice in good standing with your respective bar, legal professional in good standing,\n    law student or legal support staff\n- type: business\n  text: A law firm, legal department, law school or business entity that wishes to use Paladin’s Services.\n- type: nonprofit\n  text: A bar organization, onprofit or legal aid organization that wishes to partner with Paladin to facilitate\n    their pro\
  \ bono.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 18+ years old.\n"
source_yaml_url: https://artifacts.apis.io/paladin/eligibility/paladin-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Paladin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal
- Legal Tech
- Pro Bono
- Legal Services
- Volunteer Management
- Program Management
- Compliance
---
