---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: a country subject to a United States embargo (as of the Effective Date, Cuba, Iran, North Korea, Sudan, and Syria)
  entity_types:
  - text: you, an individual executing this Agreement
    type: individual
  - source: https://www.lingco.io/acceptable_use_policy
    text: you are of legal age to form a binding contract with Lingco
    type: individual
  minimum_age:
    source: https://www.lingco.io/acceptable_use_policy
    text: This Website is offered and available to users who are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Excluded regulated data
    text: Customer represents and warrants that Customer Data does not and will not include
  - summary: FERPA student information
    text: Lingco may not disclose or share any Student Information to any other party or for any other purpose without the prior written consent of the student.
  - source: https://www.lingco.io/acceptable_use_policy
    summary: Harm to minors
    text: For the purpose of exploiting, harming, or attempting to exploit or harm minors in any way
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Lingco Language Labs
provenance_date: '2026-11-09'
provider_name: Lingco Language Labs
provider_slug: lingco-language-labs
slug: lingco-language-labs-eligibility
source_date: '2026-11-09'
source_filename: lingco-language-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.lingco.io/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lingco Language Labs\naid: lingco-language-labs\nurl: https://www.lingco.io/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.lingco.io/acceptable_use_policy\n  - https://www.lingco.io/terms_of_service\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: a country subject to a United States embargo (as of the Effective Date, Cuba, Iran, North Korea, Sudan,\n    and Syria)\nentity_types:\n- type: individual\n  text: you, an individual executing this Agreement\n- type: individual\n  text: you are of legal age to form a binding contract with Lingco\n  source:\
  \ https://www.lingco.io/acceptable_use_policy\nrestricted_uses:\n- summary: Excluded regulated data\n  text: Customer represents and warrants that Customer Data does not and will not include\n- summary: FERPA student information\n  text: Lingco may not disclose or share any Student Information to any other party or for any other purpose without\n    the prior written consent of the student.\n- summary: Harm to minors\n  text: For the purpose of exploiting, harming, or attempting to exploit or harm minors in any way\n  source: https://www.lingco.io/acceptable_use_policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Website is offered and available to users who are 13 years of age or older\n  source: https://www.lingco.io/acceptable_use_policy\n"
source_yaml_url: https://artifacts.apis.io/lingco-language-labs/eligibility/lingco-language-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Lingco Language Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Language Learning
- LMS
- LTI
- OneRoster
- Rostering
- SSO
- Interoperability
---
