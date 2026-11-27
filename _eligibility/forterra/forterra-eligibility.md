---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: User certifies to Forterra that if User is an individual (i.e., not a corporation) User is at least 18 years of age.
    type: individual
  minimum_age:
    text: User certifies to Forterra that if User is an individual (i.e., not a corporation) User is at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Void where prohibited by law
    text: This Agreement is void where prohibited by law, and the right to access the Site is revoked in such jurisdictions.
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
name: Forterra
provenance_date: '2026-11-09'
provider_name: Forterra
provider_slug: forterra
slug: forterra-eligibility
source_date: '2026-11-09'
source_filename: forterra-eligibility.yml
source_heading: Eligibility
source_page: https://www.forterra.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forterra\naid: forterra\nurl: https://www.forterra.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: User certifies to Forterra that if User is an individual (i.e., not a corporation) User is at least 18 years\n    of age.\nrestricted_uses:\n- summary: Void where prohibited by law\n  text: This Agreement is void where prohibited by law, and the right to access the Site is revoked in such jurisdictions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n\
  \  text: User certifies to Forterra that if User is an individual (i.e., not a corporation) User is at least 18 years\n    of age.\n"
source_yaml_url: https://artifacts.apis.io/forterra/eligibility/forterra-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Forterra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transportation
- Autonomous Vehicles
- Defense
- Robotics
- Autonomy
- Edge Computing
- National Security
---
