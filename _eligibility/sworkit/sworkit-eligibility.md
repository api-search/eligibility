---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the customer that accepts these Terms (“ Customer ”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with export laws
    text: Customer agrees not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired from Nexercise, or any products utilizing such data, in violation of the United States export laws or regulations.
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
name: Sworkit
provenance_date: '2026-11-10'
provider_name: Sworkit
provider_slug: sworkit
slug: sworkit-eligibility
source_date: '2026-11-10'
source_filename: sworkit-eligibility.yml
source_heading: Eligibility
source_page: https://sworkit.com/sworkit-enterprise-customer-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sworkit\naid: sworkit\nurl: https://sworkit.com/sworkit-enterprise-customer-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the customer that accepts these Terms (“ Customer ”)\nrestricted_uses:\n- summary: Compliance with export laws\n  text: Customer agrees not to export, reexport, or transfer, directly or indirectly, any U.S. technical data acquired\n    from Nexercise, or any products utilizing such data, in violation of the United States export laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sworkit/eligibility/sworkit-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sworkit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fitness
- Health and Wellness
- Employee Wellbeing
- Workouts
- Mindfulness
- Nutrition
- Embeddable Components
- SDK
---
