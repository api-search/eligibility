---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and legally able to enter this agreement.
    type: individual
  - text: If you use Basis for an organization, you confirm that you have authority to bind that organization.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter this agreement.
    value: '18'
  restricted_uses:
  - summary: Fraud, manipulation and unlawful promotion
    text: Do not use Basis for fraud, market manipulation, unlawful financial promotion, impersonation or infringement of intellectual-property or privacy rights.
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
name: Basis Charts
provenance_date: '2026-11-09'
provider_name: Basis Charts
provider_slug: basischarts-com
slug: basischarts-com-eligibility
source_date: '2026-11-09'
source_filename: basischarts-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.basischarts.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Basis Charts\naid: basischarts-com\nurl: https://www.basischarts.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter this agreement.\n- type: business\n  text: If you use Basis for an organization, you confirm that you have authority to bind that organization.\nrestricted_uses:\n- summary: Fraud, manipulation and unlawful promotion\n  text: Do not use Basis for fraud, market manipulation, unlawful financial promotion, impersonation or infringement\n    of intellectual-property\
  \ or privacy rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter this agreement.\n"
source_yaml_url: https://artifacts.apis.io/basischarts-com/eligibility/basischarts-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Basis Charts's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Trading
- Charting
- Artificial Intelligence
- Research
- Free
---
