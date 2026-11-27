---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an entity, organization, or company, or acting on behalf of one, you represent and warrant that you are an authorized representative of such entity
    type: business
  minimum_age:
    text: You represent and warrant to Litmus that you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Fraudulent undertakings
    text: You represent that you will not use the Services, directly or indirectly, for any fraudulent undertakings.
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
name: Litmus Automation
provenance_date: '2026-11-09'
provider_name: Litmus Automation
provider_slug: litmus-automation
slug: litmus-automation-eligibility
source_date: '2026-11-09'
source_filename: litmus-automation-eligibility.yml
source_heading: Eligibility
source_page: https://litmus.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Litmus Automation\naid: litmus-automation\nurl: https://litmus.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are an entity, organization, or company, or acting on behalf of one, you represent and warrant that\n    you are an authorized representative of such entity\nrestricted_uses:\n- summary: Fraudulent undertakings\n  text: You represent that you will not use the Services, directly or indirectly, for any fraudulent undertakings.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: You represent and warrant to Litmus that you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/litmus-automation/eligibility/litmus-automation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Litmus Automation's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- Industrial IoT
- Edge Computing
- Unified Namespace
- MQTT
- DataOps
- Industrial Data Platform
- Analytics
---
