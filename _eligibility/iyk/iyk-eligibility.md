---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Services. If you are between 13 and the age of majority in your jurisdiction, you must have the consent of your parent or legal guardian
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Services.
    value: '13'
  restricted_uses:
  - summary: Violation of law or Terms
    text: Access or use the Services in violation of any law, regulation, or these Terms.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access certain features, you must create an account and provide accurate, current information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: IYK
provenance_date: '2026-11-09'
provider_name: IYK
provider_slug: iyk
slug: iyk-eligibility
source_date: '2026-11-09'
source_filename: iyk-eligibility.yml
source_heading: Eligibility
source_page: https://assets.iyk.app/iyk-terms-of-service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IYK\naid: iyk\nurl: https://assets.iyk.app/iyk-terms-of-service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Services. If you are between 13 and the age of majority in\n    your jurisdiction, you must have the consent of your parent or legal guardian\nrestricted_uses:\n- summary: Violation of law or Terms\n  text: Access or use the Services in violation of any law, regulation, or these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access certain\
  \ features, you must create an account and provide accurate, current information.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/iyk/eligibility/iyk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from IYK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- NFC
- Phygital
- Blockchain
- NFT
- POAP
- Chips
- Authentication
- Fan Engagement
- Web3
---
