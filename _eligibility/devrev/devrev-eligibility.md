---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Agreement is made by and between you/your organization and all of its employees and agents
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful use
    text: (i) conduct any business that is unlawful; (ii) infringe or otherwise violate a third party’s rights;
  - summary: Protected health information
    text: Customer must not (and must not permit anyone else to) upload to the Platform (or use the Platform to process) any patient, medical or other protected health information regulated by the Health Insurance Portability and Accountability Act.
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
name: Devrev
provenance_date: '2026-11-09'
provider_name: Devrev
provider_slug: devrev
slug: devrev-eligibility
source_date: '2026-11-09'
source_filename: devrev-eligibility.yml
source_heading: Eligibility
source_page: https://devrev.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Devrev\naid: devrev\nurl: https://devrev.ai/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: This Agreement is made by and between you/your organization and all of its employees and agents\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: (i) conduct any business that is unlawful; (ii) infringe or otherwise violate a third party’s rights;\n- summary: Protected health information\n  text: Customer must not (and must not permit anyone else to) upload to the Platform (or use the Platform to process)\n\
  \    any patient, medical or other protected health information regulated by the Health Insurance Portability and\n    Accountability Act.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/devrev/eligibility/devrev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Devrev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Service
- Product Development
- Issue Tracking
- Knowledge Base
- CRM
- Developer Tools
- Artificial Intelligence
- Webhook
- Automation
---
