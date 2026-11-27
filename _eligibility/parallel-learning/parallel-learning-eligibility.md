---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Certain Services, including Telehealth Services, are currently only available to individuals located in certain states:'
  entity_types:
  - text: you, for yourself and/or on behalf of your minor child who may use the Site or the Services
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for emergencies
    text: The Services are not intended for use in the event of an emergency.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Telehealth Services are available only to Student Members who have registered with Parallel and to Providers affiliated with Parallel who have been granted Accounts with usernames and passwords
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Parallel Learning
provenance_date: '2026-11-10'
provider_name: Parallel Learning
provider_slug: parallel-learning
slug: parallel-learning-eligibility
source_date: '2026-11-10'
source_filename: parallel-learning-eligibility.yml
source_heading: Eligibility
source_page: https://www.parallellearning.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Parallel Learning\naid: parallel-learning\nurl: https://www.parallellearning.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Certain Services, including Telehealth Services, are currently only available to individuals located in\n    certain states:'\nentity_types:\n- type: individual\n  text: you, for yourself and/or on behalf of your minor child who may use the Site or the Services\nrestricted_uses:\n- summary: Not for emergencies\n  text: The Services are not intended for use in the event of an emergency.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ true\n  text: Telehealth Services are available only to Student Members who have registered with Parallel and to Providers\n    affiliated with Parallel who have been granted Accounts with usernames and passwords\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/parallel-learning/eligibility/parallel-learning-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Parallel Learning's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Special Education
- Education
- EdTech
- Teletherapy
- Healthcare
- Assessment
- Mental Health
- HIPAA
- FERPA
---
