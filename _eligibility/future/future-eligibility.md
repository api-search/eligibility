---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To use the Services, you must be at least 18 years old, unless a specific feature expressly states a different minimum age.
    type: individual
  minimum_age:
    text: you must be at least 18 years old, unless a specific feature expressly states a different minimum age.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: 'The following conduct is not permitted under any circumstances: Using the Services for any unlawful purpose or in violation of any applicable federal, state, local, or international law or regulation.'
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
name: Future
provenance_date: '2026-11-09'
provider_name: Future
provider_slug: future
slug: future-eligibility
source_date: '2026-11-09'
source_filename: future-eligibility.yml
source_heading: Eligibility
source_page: https://future.co/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Future\naid: future\nurl: https://future.co/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To use the Services, you must be at least 18 years old, unless a specific feature expressly states a different\n    minimum age.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: 'The following conduct is not permitted under any circumstances: Using the Services for any unlawful purpose\n    or in violation of any applicable federal, state, local, or international law or regulation.'\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old, unless a specific feature expressly states a different minimum age.\n"
source_yaml_url: https://artifacts.apis.io/future/eligibility/future-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Future's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Fitness
- Health
- Personal Training
- Coaching
- Wellness
- Mobile App
---
