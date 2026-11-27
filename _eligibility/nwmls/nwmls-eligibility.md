---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older and meet all of the eligibility requirements stated in these Terms of Use.
    type: individual
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Protected health information
    text: you must not submit, upload, transmit, store, or otherwise provide through the Website any medical, patient, health, treatment, insurance, or other individually identifiable health information that is regulated under the Health Insurance Portability and Accountability Act of 1996
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
name: NWMLS
provenance_date: '2026-11-10'
provider_name: NWMLS
provider_slug: nwmls
slug: nwmls-eligibility
source_date: '2026-11-10'
source_filename: nwmls-eligibility.yml
source_heading: Eligibility
source_page: https://www.nwmls.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NWMLS\naid: nwmls\nurl: https://www.nwmls.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older and meet all of the eligibility\n    requirements stated in these Terms of Use.\nrestricted_uses:\n- summary: Protected health information\n  text: you must not submit, upload, transmit, store, or otherwise provide through the Website any medical, patient,\n    health, treatment,\
  \ insurance, or other individually identifiable health information that is regulated under\n    the Health Insurance Portability and Accountability Act of 1996\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/nwmls/eligibility/nwmls-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from NWMLS's own page on 2026-11-10.
synthetic: false
tags:
- Company
---
