---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are thirteen (13) years of age or older at the time of registering for an account on Sitter.com or Petsitter.com, and that you are eighteen (18) years of age or older at the time of registering for an account on any other Website.
    value: 13 or 18
  restricted_uses:
  - summary: Lawful use only
    text: you agree to use the Platform and Services for lawful purposes only and in a manner consistent with all applicable local, national or international laws and regulations
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: CareGuide does not verify, review, evaluate, interview, screen or perform any background checks on any of its Users or the content posted by the User on the Platform.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CareGuide
provenance_date: '2026-11-09'
provider_name: CareGuide
provider_slug: careguide
slug: careguide-eligibility
source_date: '2026-11-09'
source_filename: careguide-eligibility.yml
source_heading: Eligibility
source_page: https://www.careguide.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CareGuide\naid: careguide\nurl: https://www.careguide.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: you agree to use the Platform and Services for lawful purposes only and in a manner consistent with all\n    applicable local, national or international laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: CareGuide does not verify, review, evaluate, interview, screen or perform any background checks on any of\n    its Users or the content\
  \ posted by the User on the Platform.\nminimum_age:\n  value: 13 or 18\n  text: you are thirteen (13) years of age or older at the time of registering for an account on Sitter.com or Petsitter.com,\n    and that you are eighteen (18) years of age or older at the time of registering for an account on any other\n    Website.\n"
source_yaml_url: https://artifacts.apis.io/careguide/eligibility/careguide-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from CareGuide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Care
- Marketplace
- Caregiving
- Childcare
- Elder Care
- Pet Care
- Payroll
- Consumer
---
