---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to use the Website.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the Website.
    value: '16'
  restricted_uses:
  - summary: High-risk decisions
    text: to use the Services for high-risk decisions where errors could cause harm without appropriate independent checks (for example, legal, medical, or financial decisions).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access the Services, you may need to create an account by authenticating your email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rodeo
provenance_date: '2026-11-09'
provider_name: Rodeo
provider_slug: gorodeo-app
slug: gorodeo-app-eligibility
source_date: '2026-11-09'
source_filename: gorodeo-app-eligibility.yml
source_heading: Eligibility
source_page: https://docs.gorodeo.app/introduction/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rodeo\naid: gorodeo-app\nurl: https://docs.gorodeo.app/introduction/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Website.\nrestricted_uses:\n- summary: High-risk decisions\n  text: to use the Services for high-risk decisions where errors could cause harm without appropriate independent\n    checks (for example, legal, medical, or financial decisions).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access the Services, you may need to\
  \ create an account by authenticating your email address.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Website.\n"
source_yaml_url: https://artifacts.apis.io/gorodeo-app/eligibility/gorodeo-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Rodeo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Careers
- Job Search
- Startups
- Closed
---
