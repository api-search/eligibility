---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using this Site, you represent, acknowledge and agree that you are at least 18 years of age, or if you are under 18 years of age but are at least 13 years old (a “Minor”)
    type: individual
  minimum_age:
    text: If you are not at least 13 years old, you may not use the Site at any time or in any manner or submit any information to Certemy or the Site.
    value: '13'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once you have submitted your account registration information, Certemy administrator shall have the right to approve or reject the requested registration, in Certemy administrator’s sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Certemy
provenance_date: '2026-11-09'
provider_name: Certemy
provider_slug: certemy
slug: certemy-eligibility
source_date: '2026-11-09'
source_filename: certemy-eligibility.yml
source_heading: Eligibility
source_page: https://certemy.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Certemy\naid: certemy\nurl: https://certemy.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using this Site, you represent, acknowledge and agree that you are at least 18 years of age, or if you\n    are under 18 years of age but are at least 13 years old (a “Minor”)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once you have submitted your account registration information, Certemy administrator shall have the right\n    to approve or reject the requested\
  \ registration, in Certemy administrator’s sole discretion.\nminimum_age:\n  value: '13'\n  text: If you are not at least 13 years old, you may not use the Site at any time or in any manner or submit any\n    information to Certemy or the Site.\n"
source_yaml_url: https://artifacts.apis.io/certemy/eligibility/certemy-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Certemy's own page on 2026-11-09.
synthetic: false
tags:
- Workforce Compliance
- License Management
- Credential Verification
- Employee Onboarding
- HRIS Integration
- Enterprise Software
---
