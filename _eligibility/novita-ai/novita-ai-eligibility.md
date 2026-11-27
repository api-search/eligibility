---
api_specs:
- filename: novita-ai-openai-api-openapi.yml
  format: yaml
  label: Novita AI Openai API
  slug: novita-ai-openai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/novita-ai/openapi/novita-ai-openai-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: you must be a natural person of at least age 18
    type: individual
  - text: or a legal entity duly registered. If you decide to create an Account for your Organization, you represent that you have the authority to act on behalf of your Organization
    type: business
  minimum_age:
    text: The Site and Marketplace Offerings are intended solely for adults. We do not knowingly collect personal information from individuals under the age of 18 ("Minors").
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You shall not use the Site or the Marketplace Offerings for any unlawful or unauthorized purpose
  - summary: Export control and sanctions
    text: You represent and warrant that you are not located in a country subject to a U.S. government embargo and are not listed on any U.S. government restricted or denied party list.
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
name: Novita AI
provenance_date: '2026-11-10'
provider_name: Novita AI
provider_slug: novita-ai
slug: novita-ai-eligibility
source_date: '2026-11-10'
source_filename: novita-ai-eligibility.yml
source_heading: Eligibility
source_page: https://novita.ai/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Novita AI\naid: novita-ai\nurl: https://novita.ai/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: individual\n  text: you must be a natural person of at least age 18\n- type: business\n  text: or a legal entity duly registered. If you decide to create an Account for your Organization, you represent\n    that you have the authority\
  \ to act on behalf of your Organization\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You shall not use the Site or the Marketplace Offerings for any unlawful or unauthorized purpose\n- summary: Export control and sanctions\n  text: You represent and warrant that you are not located in a country subject to a U.S. government embargo and\n    are not listed on any U.S. government restricted or denied party list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and Marketplace Offerings are intended solely for adults. We do not knowingly collect personal\n    information from individuals under the age of 18 (\"Minors\").\n"
source_yaml_url: https://artifacts.apis.io/novita-ai/eligibility/novita-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Novita AI's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Inference
- GPU
- OpenAI-Compatible
- Image Generation
- Video Generation
- Audio
- Embeddings
- Sandbox
- MCP
- A2A
---
