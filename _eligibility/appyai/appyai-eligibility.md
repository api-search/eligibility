---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Agreement on behalf of a legal entity, you represent that you have the authority to bind such entity to this Agreement, in which case the terms "you" or "your" refer to such entity.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Sensitive Information
    text: neither Customer nor its Authorized Users will submit any Sensitive Information through the Platform or any AI Agent.
  - summary: Prohibited AI Agent content and illegal activity
    text: not to engage in any illegal activity or in any activity that has a high risk of physical or economic harm
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
name: Appyai
provenance_date: '2026-11-09'
provider_name: Appyai
provider_slug: appyai
slug: appyai-eligibility
source_date: '2026-11-09'
source_filename: appyai-eligibility.yml
source_heading: Eligibility
source_page: https://appy.ai/platform/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Appyai\naid: appyai\nurl: https://appy.ai/platform/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Agreement on behalf of a legal entity, you represent that you have the authority\n    to bind such entity to this Agreement, in which case the terms \"you\" or \"your\" refer to such entity.\nrestricted_uses:\n- summary: No Sensitive Information\n  text: neither Customer nor its Authorized Users will submit any Sensitive Information through the Platform or\n    any AI Agent.\n\
  - summary: Prohibited AI Agent content and illegal activity\n  text: not to engage in any illegal activity or in any activity that has a high risk of physical or economic harm\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appyai/eligibility/appyai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Appyai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Analytics
- Automation
- Machine Learning
---
