---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: (iii) non-profits
    type: nonprofit
  - text: (ii) any government, governmental subdivision, regulatory or administrative body
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Significant load testing
    text: Perform significant load testing of the SaaS Software without Serverless's prior written consent.
  - summary: Peer-to-peer sharing or crypto mining
    text: Use the Services for peer-to-peer file sharing or cryptocurrency mining.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Serverless reserves the right to determine if an individual or organization is considered a Free User.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Serverless
provenance_date: '2026-11-10'
provider_name: Serverless
provider_slug: serverless
slug: serverless-eligibility
source_date: '2026-11-10'
source_filename: serverless-eligibility.yml
source_heading: Eligibility
source_page: https://www.serverless.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Serverless\naid: serverless\nurl: https://www.serverless.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: nonprofit\n  text: (iii) non-profits\n- type: government\n  text: (ii) any government, governmental subdivision, regulatory or administrative body\nrestricted_uses:\n- summary: Significant load testing\n  text: Perform significant load testing of the SaaS Software without Serverless's prior written consent.\n- summary: Peer-to-peer sharing or crypto mining\n  text: Use the Services for peer-to-peer file sharing or cryptocurrency mining.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Serverless reserves the right to determine if an individual or organization is considered a Free User.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/serverless/eligibility/serverless-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Serverless's own page on 2026-11-10.
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
