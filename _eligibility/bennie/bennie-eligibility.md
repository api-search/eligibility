---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Service is hosted in the United States and is intended only for users located in the United States.
  entity_types:
  - text: Users are only eligible to register for an account and/or use the Service if they are a participating and eligible employee (or, if applicable, eligible dependent of such an employee) of an employer that has separately contracted with Bennie
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Under-13 users barred
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
  - summary: Minors need parental approval
    text: if you are under 18 years old, you may use the Service, with or without registering, only with the approval of your parent or guardian.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Bennie may delay your registration or take other actions as needed to validate or authenticate your account and eligibility.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bennie
provenance_date: '2026-11-09'
provider_name: Bennie
provider_slug: bennie
slug: bennie-eligibility
source_date: '2026-11-09'
source_filename: bennie-eligibility.yml
source_heading: Eligibility
source_page: https://www.bennie.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bennie\naid: bennie\nurl: https://www.bennie.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Service is hosted in the United States and is intended only for users located in the United States.\nentity_types:\n- type: individual\n  text: Users are only eligible to register for an account and/or use the Service if they are a participating and\n    eligible employee (or, if applicable, eligible dependent of such an employee) of an employer that has separately\n    contracted with Bennie\nrestricted_uses:\n- summary: Under-13 users barred\n\
  \  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n- summary: Minors need parental approval\n  text: if you are under 18 years old, you may use the Service, with or without registering, only with the approval\n    of your parent or guardian.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Bennie may delay your registration or take other actions as needed to validate or authenticate your account\n    and eligibility.\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/bennie/eligibility/bennie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bennie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Benefits
- Human Resources
- Software-as-a-Service
- Insurance
- Employee Benefits
---
