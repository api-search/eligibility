---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'By registering and using the Services, you represent and warrant you: (i) have the authority and capacity to enter this Agreement; (ii) are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian to use the Services'
    type: individual
  minimum_age:
    text: are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian to use the Services
    value: '13'
  restricted_uses:
  - summary: Unlawful or unauthorized use
    text: Use the Services for any unlawful activities or in violation of any laws, regulations, or contractual provisions, or to induce others to do or engage in the same;
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
name: First Bite
provenance_date: '2026-11-09'
provider_name: First Bite
provider_slug: first-bite
slug: first-bite-eligibility
source_date: '2026-11-09'
source_filename: first-bite-eligibility.yml
source_heading: Eligibility
source_page: https://app.firstbite.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: First Bite\naid: first-bite\nurl: https://app.firstbite.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'By registering and using the Services, you represent and warrant you: (i) have the authority and capacity\n    to enter this Agreement; (ii) are at least 18 years old, or 13 years or older and have the express permission\n    of your parent or guardian to use the Services'\nrestricted_uses:\n- summary: Unlawful or unauthorized use\n  text: Use the Services for any unlawful activities or in violation of any laws,\
  \ regulations, or contractual provisions,\n    or to induce others to do or engage in the same;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian\n    to use the Services\n"
source_yaml_url: https://artifacts.apis.io/first-bite/eligibility/first-bite-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from First Bite's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Service
- Sales Platform
- CRM
- Data
---
