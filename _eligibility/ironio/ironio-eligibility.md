---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: provided that you are of legal age and standing to form a binding contract
    value: legal age
  restricted_uses:
  - summary: Legal and proper purposes only
    text: such conduct shall be only for purposes that are legal, proper and in accordance with the provisions of these Terms and the Iron.io Applicable Use Policy
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you may be required to provide current and accurate identification, including a valid email address, and other information as part of the registration process
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Iron.io
provenance_date: '2026-11-09'
provider_name: Iron.io
provider_slug: ironio
slug: ironio-eligibility
source_date: '2026-11-09'
source_filename: ironio-eligibility.yml
source_heading: Eligibility
source_page: https://www.iron.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Iron.io\naid: ironio\nurl: https://www.iron.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Legal and proper purposes only\n  text: such conduct shall be only for purposes that are legal, proper and in accordance with the provisions of\n    these Terms and the Iron.io Applicable Use Policy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you may be required to provide current and accurate identification, including a valid email address, and\n    other information as part of the registration\
  \ process\nminimum_age:\n  value: legal age\n  text: provided that you are of legal age and standing to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/ironio/eligibility/ironio-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Iron.io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- Message Queue
- Serverless
- Background Jobs
- Task Processing
- Cache
- Messaging
---
