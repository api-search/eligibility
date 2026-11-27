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
  - summary: Spend limits not for hazardous or critical systems
    text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of any hazardous environments or critical systems
  - summary: No cryptocurrency mining
    text: You will not use, and will not facilitate or allow End Users to use, the Services to mine cryptocurrency.
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
name: AWS CLI
provenance_date: '2026-11-09'
provider_name: AWS CLI
provider_slug: aws-cli
slug: aws-cli-eligibility
source_date: '2026-11-09'
source_filename: aws-cli-eligibility.yml
source_heading: Eligibility
source_page: https://aws.amazon.com/service-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AWS CLI\naid: aws-cli\nurl: https://aws.amazon.com/service-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Spend limits not for hazardous or critical systems\n  text: Spend limits are not intended for accounts or projects used in, or in association with, the operation of\n    any hazardous environments or critical systems\n- summary: No cryptocurrency mining\n  text: You will not use, and will not facilitate or allow End Users to use, the Services to mine cryptocurrency.\nverification:\n  kyc: null\n \
  \ kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aws-cli/eligibility/aws-cli-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from AWS CLI's own page on 2026-11-09.
synthetic: false
tags:
- Amazon Web Services
- CLI
- Cloud Computing
- Command Line Interface
- DevOps
- Open Source
---
