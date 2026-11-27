---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served:
    - US
    text: You must be 13 years of age or older and reside in the United States or any of its territories to use the Services. ... any country that has been designated by the U.S. Government as a “terrorist supporting”(currently, the Crimea region of Ukraine, Cuba, Iran, North Korea, and Syria)
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity, and you represent and warrant that (a) you are an authorized representative of the entity
    type: business
  minimum_age:
    text: You must be 13 years of age or older and reside in the United States or any of its territories to use the Services.
    value: '13'
  restricted_uses:
  - summary: Prohibited persons
    text: you may not use or access the Services if you are a Prohibited Person
  - summary: Sanctions compliance (platform)
    text: engage in any activity that may be in violation of regulations administered by the United States Department of the Treasury’s Office of Foreign Assets Control
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To verify your identity, to approve or decline payment transactions, and to detect and prevent fraud, we may obtain information about you from third-party providers.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clerq
provenance_date: '2026-11-09'
provider_name: Clerq
provider_slug: clerq
slug: clerq-eligibility
source_date: '2026-11-09'
source_filename: clerq-eligibility.yml
source_heading: Eligibility
source_page: https://www.clerq.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clerq\naid: clerq\nurl: https://www.clerq.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You must be 13 years of age or older and reside in the United States or any of its territories to use the\n    Services. ... any country that has been designated by the U.S. Government as a “terrorist supporting”(currently,\n    the Crimea region of Ukraine, Cuba, Iran, North Korea, and Syria)\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then “you” includes you and that entity,\n\
  \    and you represent and warrant that (a) you are an authorized representative of the entity\nrestricted_uses:\n- summary: Prohibited persons\n  text: you may not use or access the Services if you are a Prohibited Person\n- summary: Sanctions compliance (platform)\n  text: engage in any activity that may be in violation of regulations administered by the United States Department\n    of the Treasury’s Office of Foreign Assets Control\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To verify your identity, to approve or decline payment transactions, and to detect and prevent fraud, we\n    may obtain information about you from third-party providers.\nminimum_age:\n  value: '13'\n  text: You must be 13 years of age or older and reside in the United States or any of its territories to use the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/clerq/eligibility/clerq-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Clerq's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Fintech
- Banking
- B2B
---
