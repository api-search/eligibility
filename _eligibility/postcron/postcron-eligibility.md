---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is available only to individuals who are at least 16 years old.
    type: individual
  minimum_age:
    text: The Website is available only to individuals who are at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: No unlawful use
    text: User shall not use the Service or any Content for any purpose that is unlawful or prohibited by this Agreement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Postcron reserves the right to refuse registration of, or cancel a Postcron User in its discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Postcron
provenance_date: '2026-11-10'
provider_name: Postcron
provider_slug: postcron
slug: postcron-eligibility
source_date: '2026-11-10'
source_filename: postcron-eligibility.yml
source_heading: Eligibility
source_page: https://postcron.com/en/terms_conditions_privacy_policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Postcron\naid: postcron\nurl: https://postcron.com/en/terms_conditions_privacy_policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is available only to individuals who are at least 16 years old.\nrestricted_uses:\n- summary: No unlawful use\n  text: User shall not use the Service or any Content for any purpose that is unlawful or prohibited by this Agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Postcron reserves the right to refuse registration of, or cancel a Postcron User in\
  \ its discretion.\nminimum_age:\n  value: '16'\n  text: The Website is available only to individuals who are at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/postcron/eligibility/postcron-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Postcron's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- Social Media Scheduling
- Publishing
- Marketing
- Content Management
- Software-as-a-Service
- Scheduling
- Automation
---
