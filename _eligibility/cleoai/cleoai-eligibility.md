---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for an organisation, you must have authority to bind it.
    type: business
  minimum_age:
    text: Cleo users must be at least 16 and have the authority required for their role.
    value: '16'
  restricted_uses:
  - summary: Fraud, spam, impersonation
    text: Do not send unlawful spam, misleading messages, harassment or abusive content. Do not impersonate others or use the services for fraud.
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
name: Cleoai
provenance_date: '2026-11-09'
provider_name: Cleoai
provider_slug: cleoai
slug: cleoai-eligibility
source_date: '2026-11-09'
source_filename: cleoai-eligibility.yml
source_heading: Eligibility
source_page: https://www.fastcollab.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cleoai\naid: cleoai\nurl: https://www.fastcollab.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for an organisation, you must have authority to bind it.\nrestricted_uses:\n- summary: Fraud, spam, impersonation\n  text: Do not send unlawful spam, misleading messages, harassment or abusive content. Do not impersonate others\n    or use the services for fraud.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Cleo users must be at least 16 and have\
  \ the authority required for their role.\n"
source_yaml_url: https://artifacts.apis.io/cleoai/eligibility/cleoai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cleoai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Service
- Software-as-a-Service
- Automation
---
