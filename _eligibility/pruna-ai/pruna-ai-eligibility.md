---
api_specs:
- filename: pruna-ai-content-delivery-api-openapi.yml
  format: yaml
  label: Pruna AI Content Delivery API
  slug: pruna-ai-content-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pruna-ai/openapi/pruna-ai-content-delivery-api-openapi.yml
- filename: pruna-ai-file-management-api-openapi.yml
  format: yaml
  label: Pruna AI File Management API
  slug: pruna-ai-file-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pruna-ai/openapi/pruna-ai-file-management-api-openapi.yml
- filename: pruna-ai-predictions-api-openapi.yml
  format: yaml
  label: Pruna AI Predictions API
  slug: pruna-ai-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pruna-ai/openapi/pruna-ai-predictions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: access or use the Service if you are located in, organized under the laws of, or ordinarily resident in a country or territory subject to comprehensive U.S., EU, or UN sanctions
  entity_types:
  - text: the legal entity you represent (" Customer ", "you") accepts these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-stakes automated decisions
    text: use the Service to automate high-stakes decisions in sensitive areas such as health, safety, law enforcement, credit, housing, or other essential rights or services without appropriate human oversight
  - summary: Unlicensed professional practice
    text: engage in unauthorized or unlicensed professional practices (including financial, legal, or medical services)
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
name: Pruna AI
provenance_date: '2026-11-10'
provider_name: Pruna AI
provider_slug: pruna-ai
slug: pruna-ai-eligibility
source_date: '2026-11-10'
source_filename: pruna-ai-eligibility.yml
source_heading: Eligibility
source_page: https://docs.api.pruna.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pruna AI\naid: pruna-ai\nurl: https://docs.api.pruna.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: access or use the Service if you are located in, organized under the laws of, or ordinarily resident in\n    a country or territory subject to comprehensive U.S., EU, or UN sanctions\nentity_types:\n- type: business\n  text: the legal entity you represent (\" Customer \", \"you\") accepts these Terms.\nrestricted_uses:\n- summary: High-stakes automated decisions\n  text: use the Service to automate high-stakes decisions in sensitive areas such as health, safety, law enforcement,\n\
  \    credit, housing, or other essential rights or services without appropriate human oversight\n- summary: Unlicensed professional practice\n  text: engage in unauthorized or unlicensed professional practices (including financial, legal, or medical services)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pruna-ai/eligibility/pruna-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Pruna AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Image Generation
- Video Generation
- Generative AI
- Model Optimization
- Inference
- Developer Tools
---
