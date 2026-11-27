---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Services are intended for access and use only by U.S. customers.
  entity_types:
  - text: By using the Services, you affirm that you are of legal age and have full authority to enter into this Agreement
    type: individual
  minimum_age:
    text: The Services are not targeted toward or intended for use by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Emergency care not provided
    text: EXPRESSABLE DOES NOT PROVIDE EMERGENCY CARE.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You agree to provide us with proof of identity upon request.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Expressable
provenance_date: '2026-11-09'
provider_name: Expressable
provider_slug: expressable
slug: expressable-eligibility
source_date: '2026-11-09'
source_filename: expressable-eligibility.yml
source_heading: Eligibility
source_page: https://www.expressable.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Expressable\naid: expressable\nurl: https://www.expressable.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Services are intended for access and use only by U.S. customers.\nentity_types:\n- type: individual\n  text: By using the Services, you affirm that you are of legal age and have full authority to enter into this Agreement\nrestricted_uses:\n- summary: Emergency care not provided\n  text: EXPRESSABLE DOES NOT PROVIDE EMERGENCY CARE.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You agree to provide us with proof\
  \ of identity upon request.\nminimum_age:\n  value: '18'\n  text: The Services are not targeted toward or intended for use by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/expressable/eligibility/expressable-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Expressable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Speech Therapy
- Teletherapy
- Digital Health
- Consumer Health
- Behavioral Health
---
