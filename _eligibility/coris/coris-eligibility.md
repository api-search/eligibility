---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Coris makes no claims that the Services may be lawfully viewed, downloaded, or accessed outside of the United States.
  entity_types:
  - text: “Customer” means the company or legal entity purchasing access to the Services.
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services
  - summary: Illegal or inconsistent use
    text: You agree and warrant that you will not use the Services in a manner that is illegal or otherwise inconsistent with these Terms.
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
name: Coris
provenance_date: '2026-11-09'
provider_name: Coris
provider_slug: coris
slug: coris-eligibility
source_date: '2026-11-09'
source_filename: coris-eligibility.yml
source_heading: Eligibility
source_page: https://www.coris.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coris\naid: coris\nurl: https://www.coris.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Coris makes no claims that the Services may be lawfully viewed, downloaded, or accessed outside of the United\n    States.\nentity_types:\n- type: business\n  text: “Customer” means the company or legal entity purchasing access to the Services.\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services\n- summary: Illegal or inconsistent use\n  text: You agree and warrant\
  \ that you will not use the Services in a manner that is illegal or otherwise inconsistent\n    with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/coris/eligibility/coris-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Coris's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Risk Management
- Fraud Prevention
- Payments
- Merchant Onboarding
- KYB
- Underwriting
- Artificial Intelligence
---
