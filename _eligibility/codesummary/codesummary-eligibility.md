---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old (and the age of majority in your jurisdiction if older) to use the Services.
    type: individual
  - text: If you use the Services on behalf of an organization, you represent that you have authority to bind that organization, and "you" refers to that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old (and the age of majority in your jurisdiction if older) to use the Services.
    value: '16'
  restricted_uses:
  - summary: Violations of law or third-party rights
    text: use the Services in violation of any law or to infringe, misappropriate, or violate the rights of others
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
name: Code Summary
provenance_date: '2026-11-09'
provider_name: Code Summary
provider_slug: codesummary
slug: codesummary-eligibility
source_date: '2026-11-09'
source_filename: codesummary-eligibility.yml
source_heading: Eligibility
source_page: https://codesummary.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Code Summary\naid: codesummary\nurl: https://codesummary.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old (and the age of majority in your jurisdiction if older) to use the Services.\n- type: business\n  text: If you use the Services on behalf of an organization, you represent that you have authority to bind that\n    organization, and \"you\" refers to that organization.\nrestricted_uses:\n- summary: Violations of law or third-party rights\n  text: use the Services in violation of any law\
  \ or to infringe, misappropriate, or violate the rights of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old (and the age of majority in your jurisdiction if older) to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/codesummary/eligibility/codesummary-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Code Summary's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Documentation
- Artificial Intelligence
- Knowledge
- Platform
---
