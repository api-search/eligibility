---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Carewell from its facilities in the United States of America. Carewell makes no representations that the Services is appropriate or available for use in other locations.
  entity_types:
  - text: YOU ARE AN INDIVIDUAL THAT IS NOT AT LEAST 18 YEARS OLD
    type: individual
  - text: IF THE INDIVIDUAL ENTERING INTO THIS AGREEMENT OR OTHERWISE ACCESSING OR USING THE SERVICES IS DOING SO ON BEHALF OF, OR WITHIN HIS OR HER CAPACITY AS A REPRESENTATIVE, AGENT, OR EMPLOYEE OF AN ENTITY
    type: business
  minimum_age:
    text: By using this service, you represent and warrant that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Fraud, resale and benefits misuse
    text: Carewell reserves the right to decline or limit transactions associated with suspected fraud, abuse, reimbursement manipulation, resale activity, or misuse of healthcare-related benefits or programs.
  - summary: No medical advice
    text: CAREWELL DOES NOT PROVIDE ANY FORM OF MEDICAL CARE, MEDICAL OPINION, MEDICAL ADVICE, DIAGNOSIS, OR TREATMENT
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
name: Carewell
provenance_date: '2026-11-09'
provider_name: Carewell
provider_slug: carewell
slug: carewell-eligibility
source_date: '2026-11-09'
source_filename: carewell-eligibility.yml
source_heading: Eligibility
source_page: https://www.carewell.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carewell\naid: carewell\nurl: https://www.carewell.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Carewell from its facilities in the United States of America.\n    Carewell makes no representations that the Services is appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: YOU ARE AN INDIVIDUAL THAT IS NOT AT LEAST 18 YEARS OLD\n- type: business\n  text: IF THE INDIVIDUAL ENTERING INTO THIS AGREEMENT OR OTHERWISE ACCESSING OR USING THE SERVICES IS DOING SO\n    ON BEHALF OF,\
  \ OR WITHIN HIS OR HER CAPACITY AS A REPRESENTATIVE, AGENT, OR EMPLOYEE OF AN ENTITY\nrestricted_uses:\n- summary: Fraud, resale and benefits misuse\n  text: Carewell reserves the right to decline or limit transactions associated with suspected fraud, abuse, reimbursement\n    manipulation, resale activity, or misuse of healthcare-related benefits or programs.\n- summary: No medical advice\n  text: CAREWELL DOES NOT PROVIDE ANY FORM OF MEDICAL CARE, MEDICAL OPINION, MEDICAL ADVICE, DIAGNOSIS, OR TREATMENT\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using this service, you represent and warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/carewell/eligibility/carewell-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Carewell's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Medical
- Retail
- E-Commerce
- Healthcare
---
