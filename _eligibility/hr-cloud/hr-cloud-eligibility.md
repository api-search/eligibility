---
claim_count: 1
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
  - summary: Unlawful or harmful content
    text: 'develop, generate, transmit or store, information that: (I) is defamatory, harmful, abusive, obscene or hateful'
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
name: HR Cloud
provenance_date: '2026-11-09'
provider_name: HR Cloud
provider_slug: hr-cloud
slug: hr-cloud-eligibility
source_date: '2026-11-09'
source_filename: hr-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://www.hrcloud.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HR Cloud\naid: hr-cloud\nurl: https://www.hrcloud.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or harmful content\n  text: 'develop, generate, transmit or store, information that: (I) is defamatory, harmful, abusive, obscene or\n    hateful'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hr-cloud/eligibility/hr-cloud-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from HR Cloud's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Software-as-a-Service
- Frontline
- Artificial Intelligence
---
