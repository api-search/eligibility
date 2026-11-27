---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or spam content
    text: The User is expressly prohibited from using the Services for unlawful acts or for acts otherwise prohibited under applicable law and regulations
  - summary: Unsolicited commercial email
    text: constitutes unsolicited commercial electronic messages ("spam");
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
name: Lettermint
provenance_date: '2026-11-09'
provider_name: Lettermint
provider_slug: lettermint
slug: lettermint-eligibility
source_date: '2026-11-09'
source_filename: lettermint-eligibility.yml
source_heading: Eligibility
source_page: https://lettermint.co/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lettermint\naid: lettermint\nurl: https://lettermint.co/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or spam content\n  text: The User is expressly prohibited from using the Services for unlawful acts or for acts otherwise prohibited\n    under applicable law and regulations\n- summary: Unsolicited commercial email\n  text: constitutes unsolicited commercial electronic messages (\"spam\");\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/lettermint/eligibility/lettermint-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Lettermint's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Transactional
- European
---
