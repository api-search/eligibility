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
  - summary: US export restrictions
    text: Customer may not remove or export, or allow to be removed or exported, from the United States anything related to the Platform, including the Results
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
name: Fixify
provenance_date: '2026-11-09'
provider_name: Fixify
provider_slug: fixify
slug: fixify-eligibility
source_date: '2026-11-09'
source_filename: fixify-eligibility.yml
source_heading: Eligibility
source_page: https://www.fixify.com/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fixify\naid: fixify\nurl: https://www.fixify.com/msa\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: US export restrictions\n  text: Customer may not remove or export, or allow to be removed or exported, from the United States anything related\n    to the Platform, including the Results\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fixify/eligibility/fixify-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Fixify's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- ITSM
- Help Desk
- IT Automation
- Artificial Intelligence
- Support
- Software-as-a-Service
---
