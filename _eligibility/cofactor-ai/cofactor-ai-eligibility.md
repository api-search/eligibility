---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: in connection with your employment or provision of services to the entity that has purchased a license for you to access and use such Services
    type: business
  minimum_age:
    text: 'You represent and warrant that you: (a) are of legal age to form a binding contract;'
    value: legal age
  restricted_uses:
  - summary: Consumer reports under FCRA
    text: use the Services in any way that is intended to contribute or constitute a “consumer report” under the Fair Credit Reporting Act
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
name: Cofactor AI
provenance_date: '2026-11-09'
provider_name: Cofactor AI
provider_slug: cofactor-ai
slug: cofactor-ai-eligibility
source_date: '2026-11-09'
source_filename: cofactor-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.cofactorai.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cofactor AI\naid: cofactor-ai\nurl: https://www.cofactorai.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: in connection with your employment or provision of services to the entity that has purchased a license for\n    you to access and use such Services\nrestricted_uses:\n- summary: Consumer reports under FCRA\n  text: use the Services in any way that is intended to contribute or constitute a “consumer report” under the Fair\n    Credit Reporting Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: legal age\n  text: 'You represent and warrant that you: (a) are of legal age to form a binding contract;'\n"
source_yaml_url: https://artifacts.apis.io/cofactor-ai/eligibility/cofactor-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Cofactor AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Artificial Intelligence
- Platform
- Analytics
---
