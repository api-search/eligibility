---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Affiliates must be 18 years or older, with an active website, blog, or social media presence relevant to WordPress or web development.
    type: individual
  minimum_age:
    text: Affiliates must be 18 years or older
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Affiliates must apply through our website. We reserve the right to accept or reject any application.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bit Apps
provenance_date: '2026-11-09'
provider_name: Bit Apps
provider_slug: bit-integrations
slug: bit-integrations-eligibility
source_date: '2026-11-09'
source_filename: bit-integrations-eligibility.yml
source_heading: Eligibility
source_page: https://bit-integrations.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bit Apps\naid: bit-integrations\nurl: https://bit-integrations.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Affiliates must be 18 years or older, with an active website, blog, or social media presence relevant to\n    WordPress or web development.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Affiliates must apply through our website. We reserve the right to accept or reject any application.\nminimum_age:\n  value: '18'\n  text: Affiliates must be 18 years\
  \ or older\n"
source_yaml_url: https://artifacts.apis.io/bit-integrations/eligibility/bit-integrations-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Bit Apps's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automation
- WordPress
- Integration
- Artificial Intelligence
---
