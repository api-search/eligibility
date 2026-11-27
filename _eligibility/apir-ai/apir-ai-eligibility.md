---
api_specs:
- filename: apir-ai-openapi-generated.yml
  format: yaml
  label: APIR API
  slug: apir-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apir-ai/openapi/_ae-authored/apir-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Eliciting personal data
    text: (c) attempt to elicit personal data about identified individuals;
  - summary: High-risk AI systems
    text: (f) operate any AI system that would qualify as high-risk under EU AI Act Annex III without first running an independent conformity assessment.
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
name: APIR
provenance_date: '2026-11-09'
provider_name: APIR
provider_slug: apir-ai
slug: apir-ai-eligibility
source_date: '2026-11-09'
source_filename: apir-ai-eligibility.yml
source_heading: Eligibility
source_page: https://apir.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: APIR\naid: apir-ai\nurl: https://apir.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: Eliciting personal data\n  text: (c) attempt to elicit personal data about identified individuals;\n- summary: High-risk AI systems\n  text: (f) operate any AI system that would qualify as high-risk under EU AI Act Annex III without first running\n    an independent\
  \ conformity assessment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apir-ai/eligibility/apir-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from APIR's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Evidence
- Audit
- Security
- Blockchain
---
