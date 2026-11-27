---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Services can only be used by individuals that are at least sixteen (16) years old.
    value: '16'
  restricted_uses:
  - summary: Discriminatory or unlawful candidate assessment
    text: not to use the Services to assess candidates for any jobs which are unlawful, unsafe, offensive, discriminatory, or inappropriate;
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
name: TestGorilla
provenance_date: '2026-11-10'
provider_name: TestGorilla
provider_slug: testgorilla
slug: testgorilla-eligibility
source_date: '2026-11-10'
source_filename: testgorilla-eligibility.yml
source_heading: Eligibility
source_page: https://www.testgorilla.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TestGorilla\naid: testgorilla\nurl: https://www.testgorilla.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Discriminatory or unlawful candidate assessment\n  text: not to use the Services to assess candidates for any jobs which are unlawful, unsafe, offensive, discriminatory,\n    or inappropriate;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Services can only be used by individuals that are at least sixteen (16) years old.\n"
source_yaml_url: https://artifacts.apis.io/testgorilla/eligibility/testgorilla-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from TestGorilla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hiring
- Recruiting
- Talent Assessment
- Skills Testing
- Pre-Employment Testing
- Human Resources
- AI Interviews
---
