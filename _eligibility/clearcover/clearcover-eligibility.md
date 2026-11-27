---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Not all of Clearcover’s products and services, whether or not described in the Applications, are available in all areas of the United States.
  entity_types:
  - text: As a condition to using the Applications, you affirm that you are either more than 18 years of age, or an emancipated minor, or possess legal parental or guardian consent
    type: individual
  minimum_age:
    text: you affirm that you are not under the age of 13, as the Applications are not intended for children under 13.
    value: '13'
  restricted_uses:
  - summary: Gambling and unlawful use
    text: use the Applications for any form of gambling
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All insurance applications are subject to underwriting approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clearcover
provenance_date: '2026-11-09'
provider_name: Clearcover
provider_slug: clearcover
slug: clearcover-eligibility
source_date: '2026-11-09'
source_filename: clearcover-eligibility.yml
source_heading: Eligibility
source_page: https://clearcover.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clearcover\naid: clearcover\nurl: https://clearcover.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Not all of Clearcover’s products and services, whether or not described in the Applications, are available\n    in all areas of the United States.\nentity_types:\n- type: individual\n  text: As a condition to using the Applications, you affirm that you are either more than 18 years of age, or an\n    emancipated minor, or possess legal parental or guardian consent\nrestricted_uses:\n- summary: Gambling and unlawful use\n  text: use the Applications for any form of\
  \ gambling\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All insurance applications are subject to underwriting approval.\nminimum_age:\n  value: '13'\n  text: you affirm that you are not under the age of 13, as the Applications are not intended for children under\n    13.\n"
source_yaml_url: https://artifacts.apis.io/clearcover/eligibility/clearcover-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Clearcover's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Auto Insurance
- Insurtech
- Financial Services
- Claims
- Partner API
---
