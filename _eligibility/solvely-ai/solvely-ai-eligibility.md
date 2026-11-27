---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - KP
    - IR
    - SY
    served:
    - US
    text: Solvely.ai primarily operates its Services within the U.S. ... into or to a resident or national of any country that is subject to a U.S. embargo, including but not limited to Cuba, North Korea, Iran, Syria
  entity_types:
  - text: The Services are available only to individuals aged 13 and above.
    type: individual
  minimum_age:
    text: The Services are available only to individuals aged 13 and above.
    value: '13'
  restricted_uses:
  - summary: Commercial activity without approval
    text: Conducts commercial activities or sales lacking prior written approval from Solvely.ai like contests, sweepstakes, barter, advertising, or pyramid schemes
  - summary: Restricted-party and export limits
    text: Furthermore, by utilizing any of our Services, you affirm and guarantee that you are not listed on any U.S. or other government roster of individuals or entities with whom business transactions are restricted or prohibited.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: By registering, you confirm that you are not listed as a restricted individual with whom U.S. entities are prohibited from transacting.
excluded_countries:
- CU
- KP
- IR
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Solvely Ai
provenance_date: '2026-11-10'
provider_name: Solvely Ai
provider_slug: solvely-ai
slug: solvely-ai-eligibility
source_date: '2026-11-10'
source_filename: solvely-ai-eligibility.yml
source_heading: Eligibility
source_page: https://solvely.ai/term
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solvely Ai\naid: solvely-ai\nurl: https://solvely.ai/term\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded:\n  - CU\n  - KP\n  - IR\n  - SY\n  text: Solvely.ai primarily operates its Services within the U.S. ... into or to a resident or national of any\n    country that is subject to a U.S. embargo, including but not limited to Cuba, North Korea, Iran, Syria\nentity_types:\n- type: individual\n  text: The Services are available only to individuals aged 13 and above.\nrestricted_uses:\n- summary: Commercial activity without approval\n  text: Conducts commercial activities\
  \ or sales lacking prior written approval from Solvely.ai like contests, sweepstakes,\n    barter, advertising, or pyramid schemes\n- summary: Restricted-party and export limits\n  text: Furthermore, by utilizing any of our Services, you affirm and guarantee that you are not listed on any U.S.\n    or other government roster of individuals or entities with whom business transactions are restricted or prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: By registering, you confirm that you are not listed as a restricted individual with whom U.S. entities are\n    prohibited from transacting.\nminimum_age:\n  value: '13'\n  text: The Services are available only to individuals aged 13 and above.\n"
source_yaml_url: https://artifacts.apis.io/solvely-ai/eligibility/solvely-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Solvely Ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Education
- EdTech
- Study Tools
- Homework Help
- Machine Learning
- Consumer
---
