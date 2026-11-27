---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or acting on behalf of a person or entity located in, a country or territory subject to EU, Swedish, or US embargoes or sanctions
  entity_types:
  - text: The Services are intended for business and organisational use only.
    type: business
  - text: If you are a consumer, you may not use the Services unless expressly permitted in writing by Triple Alpha AB.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: High-risk use without human review
    text: Use AI Output without appropriate human review in safety-critical, medical, legal, financial, or other high-risk contexts;
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
name: Aient
provenance_date: '2026-11-09'
provider_name: Aient
provider_slug: aient-ai
slug: aient-ai-eligibility
source_date: '2026-11-09'
source_filename: aient-ai-eligibility.yml
source_heading: Eligibility
source_page: https://aient.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aient\naid: aient-ai\nurl: https://aient.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or acting on behalf of a person or entity located in,\n    a country or territory subject to EU, Swedish, or US embargoes or sanctions\nentity_types:\n- type: business\n  text: The Services are intended for business and organisational use only.\n- type: individual\n  text: If you are a consumer, you may not use the Services unless expressly permitted in writing by Triple Alpha\n    AB.\nrestricted_uses:\n- summary: High-risk use\
  \ without human review\n  text: Use AI Output without appropriate human review in safety-critical, medical, legal, financial, or other high-risk\n    contexts;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/aient-ai/eligibility/aient-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Aient's own page on 2026-11-09.
synthetic: false
tags:
- AI SRE
- Automated Fixes
- DevOps
---
