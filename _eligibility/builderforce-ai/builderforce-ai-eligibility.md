---
api_specs:
- filename: builderforce-ai-openapi-generated.yml
  format: yaml
  label: Builderforce.ai API
  slug: builderforce-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/builderforce-ai/openapi/_ae-authored/builderforce-ai-openapi-generated.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not provide the Service in embargoed locations or to prohibited parties.
  entity_types:
  - text: You must be at least 18 and able to enter this agreement.
    type: individual
  - text: The Service is for business and professional use and is not directed to children under 13.
    type: business
  minimum_age:
    text: You must be at least 18 and able to enter this agreement.
    value: '18'
  restricted_uses:
  - summary: Consequential decisions require human review
    text: applying qualified human review before deployment or use in legal, medical, financial, employment, housing, credit, insurance, safety-critical, or other consequential decisions.
  - summary: Prohibited solely automated consequential decisions
    text: make prohibited solely automated consequential decisions;
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
name: Builderforce.ai
provenance_date: '2026-11-09'
provider_name: Builderforce.ai
provider_slug: builderforce-ai
slug: builderforce-ai-eligibility
source_date: '2026-11-09'
source_filename: builderforce-ai-eligibility.yml
source_heading: Eligibility
source_page: https://builderforce.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Builderforce.ai\naid: builderforce-ai\nurl: https://builderforce.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not provide the Service in embargoed locations or to prohibited parties.\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to enter this agreement.\n- type: business\n  text: The Service is for business and professional use and is not directed to children under 13.\nrestricted_uses:\n- summary: Consequential decisions require human review\n  text: applying qualified human review before deployment or use in legal, medical,\
  \ financial, employment, housing,\n    credit, insurance, safety-critical, or other consequential decisions.\n- summary: Prohibited solely automated consequential decisions\n  text: make prohibited solely automated consequential decisions;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to enter this agreement.\n"
source_yaml_url: https://artifacts.apis.io/builderforce-ai/eligibility/builderforce-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Builderforce.ai's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Low-Code
- Marketplace
- Governance
---
