---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The right to access and use the Website and Services will not be granted in jurisdictions, if any, where it may be prohibited
  entity_types:
  - text: if the User is an academic institution, business entity, or otherwise not a natural person
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: Input, upload, transmit, or otherwise provide to or through the Website and Services, any information or materials that are unlawful or injurious, or contain, transmit, or activate any Harmful Code
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
name: Labster
provenance_date: '2026-11-09'
provider_name: Labster
provider_slug: labster
slug: labster-eligibility
source_date: '2026-11-09'
source_filename: labster-eligibility.yml
source_heading: Eligibility
source_page: https://www.labster.com/terms-of-service-and-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Labster\naid: labster\nurl: https://www.labster.com/terms-of-service-and-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The right to access and use the Website and Services will not be granted in jurisdictions, if any, where\n    it may be prohibited\nentity_types:\n- type: business\n  text: if the User is an academic institution, business entity, or otherwise not a natural person\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: Input, upload, transmit, or otherwise provide to or through the Website and Services, any information or\n    materials that are unlawful\
  \ or injurious, or contain, transmit, or activate any Harmful Code\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/labster/eligibility/labster-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Labster's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Virtual Labs
- Science Education
- STEM
- Simulation
- LMS
- LTI
- Higher Education
---
