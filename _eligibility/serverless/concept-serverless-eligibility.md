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
  - summary: Prohibited content
    text: 'Customer agrees that neither it nor its Authorized Users will display, process, or transmit any content through the Services that: Infringes or misappropriates any third-party rights'
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Free User status is determined at the time of use, purchase or renewal and must be reassessed by the Customer on a monthly basis, with the Customer responsible for honoring this classification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Serverless
provenance_date: '2026-11-09'
provider_name: Serverless
provider_slug: serverless
slug: concept-serverless-eligibility
source_date: '2026-11-09'
source_filename: concept-serverless-eligibility.yml
source_heading: Eligibility
source_page: https://www.serverless.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Serverless\naid: concept-serverless\nurl: https://www.serverless.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited content\n  text: 'Customer agrees that neither it nor its Authorized Users will display, process, or transmit any content\n    through the Services that: Infringes or misappropriates any third-party rights'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Free User status is determined at the time of use, purchase or renewal and must be reassessed by the Customer\n\
  \    on a monthly basis, with the Customer responsible for honoring this classification.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/serverless/eligibility/concept-serverless-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Serverless's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Serverless
- Infrastructure as Code
- Developer Tools
- AWS Lambda
- Deployment
- Cloud
- CLI
---
