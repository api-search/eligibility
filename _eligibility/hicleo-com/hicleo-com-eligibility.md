---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you must be 18 years of age or older and reside in a place where the Services are provided.
  entity_types:
  - text: In order to use the Services, you must be 18 years of age or older
    type: individual
  minimum_age:
    text: you must be 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: No impersonation
    text: Impersonate any person or entity, including another user, Expert, or an employee of Cleo
  - summary: No harassment or stalking
    text: Stalk or otherwise harass another user or any of our employees or Experts;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may, in our sole discretion, refuse to offer the Service or grant access to you or any other Member at any time and for any reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cleo
provenance_date: '2026-11-09'
provider_name: Cleo
provider_slug: hicleo-com
slug: hicleo-com-eligibility
source_date: '2026-11-09'
source_filename: hicleo-com-eligibility.yml
source_heading: Eligibility
source_page: https://hicleo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleo\naid: hicleo-com\nurl: https://hicleo.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you must be 18 years of age or older and reside in a place where the Services are provided.\nentity_types:\n- type: individual\n  text: In order to use the Services, you must be 18 years of age or older\nrestricted_uses:\n- summary: No impersonation\n  text: Impersonate any person or entity, including another user, Expert, or an employee of Cleo\n- summary: No harassment or stalking\n  text: Stalk or otherwise harass another user or any of our employees or Experts;\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may, in our sole discretion, refuse to offer the Service or grant access to you or any other Member at\n    any time and for any reason.\nminimum_age:\n  value: '18'\n  text: you must be 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/hicleo-com/eligibility/hicleo-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Cleo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Caregiving
- Health
- Employer
- Family
- Platform
---
