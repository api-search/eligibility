---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service through an enterprise account maintained by your organization (such as your employer, school, etc.), your usage rights are subject to the enterprise agreement between your organization and Educative.
    type: other
  minimum_age:
    text: The Services are not intended for use by anyone under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Prohibited content and conduct
    text: 'you agree to not use the Service to make available and transmit any content that, or content that promotes a product or Service that: is illegal under or otherwise violates any local, state, national or international law'
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
name: Educative
provenance_date: '2026-11-09'
provider_name: Educative
provider_slug: educative
slug: educative-eligibility
source_date: '2026-11-09'
source_filename: educative-eligibility.yml
source_heading: Eligibility
source_page: https://www.educative.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Educative\naid: educative\nurl: https://www.educative.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: If you are using the Service through an enterprise account maintained by your organization (such as your\n    employer, school, etc.), your usage rights are subject to the enterprise agreement between your organization\n    and Educative.\nrestricted_uses:\n- summary: Prohibited content and conduct\n  text: 'you agree to not use the Service to make available and transmit any content that, or content that promotes\n    a product\
  \ or Service that: is illegal under or otherwise violates any local, state, national or international\n    law'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are not intended for use by anyone under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/educative/eligibility/educative-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Educative's own page on 2026-11-09.
synthetic: false
tags:
- Courses
- Education
- Learning
- E-Learning
- Developer Training
- Interview Preparation
- EdTech
---
