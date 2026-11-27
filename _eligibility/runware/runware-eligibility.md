---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our site is primarily directed to users residing in the United Kingdom, but we offer our Services to businesses globally where legally permissible.
  entity_types:
  - text: Our API allows developers and businesses to integrate media generation and other AI capabilities into their applications
    type: developer
  minimum_age:
    text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Services.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated uses
    text: The Services are not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: Sanctioned persons
    text: you are not located in a country or territory subject to comprehensive sanctions.
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
name: Runware
provenance_date: '2026-11-10'
provider_name: Runware
provider_slug: runware
slug: runware-eligibility
source_date: '2026-11-10'
source_filename: runware-eligibility.yml
source_heading: Eligibility
source_page: https://runware.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Runware\naid: runware\nurl: https://runware.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Our site is primarily directed to users residing in the United Kingdom, but we offer our Services to businesses\n    globally where legally permissible.\nentity_types:\n- type: developer\n  text: Our API allows developers and businesses to integrate media generation and other AI capabilities into their\n    applications\nrestricted_uses:\n- summary: Industry-regulated uses\n  text: The Services are not tailored to comply with industry-specific regulations (Health\
  \ Insurance Portability\n    and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use the Services.\n- summary: Sanctioned persons\n  text: you are not located in a country or territory subject to comprehensive sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Services.\n"
source_yaml_url: https://artifacts.apis.io/runware/eligibility/runware-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Runware's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Inference
- Image Generation
- Video Generation
- Audio Generation
- Text Generation
- 3D Generation
- Generative AI
- Models
- Developer Tools
---
