---
api_specs:
- filename: inception-edit-api-openapi.yml
  format: yaml
  label: Inception Edit API
  slug: inception-edit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inception/openapi/inception-edit-api-openapi.yml
- filename: inception-fim-api-openapi.yml
  format: yaml
  label: Inception FIM API
  slug: inception-fim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inception/openapi/inception-fim-api-openapi.yml
- filename: inception-models-api-openapi.yml
  format: yaml
  label: Inception Models API
  slug: inception-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inception/openapi/inception-models-api-openapi.yml
- filename: inception-chat-completions-api-openapi.yml
  format: yaml
  label: Inception Chat Completions API
  slug: inception-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inception/openapi/inception-chat-completions-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not export or provide access to the Services into any U.S. embargoed countries or to anyone on (i) the U.S. Treasury Department’s list of Specially Designated Nationals
  entity_types:
  - text: You represent and warrant that you are an individual of legal age to form a binding contract
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization’s or entity’s behalf
    type: business
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not, you’ve received your parent’s or guardian’s permission to use the Services
    value: null
  restricted_uses:
  - summary: High-stakes decisions affecting individual rights
    text: relates to high-stakes decision making involving individual rights
  - summary: Political campaign content
    text: generates political campaign content
  - summary: Misinformation
    text: generates or spreads misinformation
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
name: Inception
provenance_date: '2026-11-09'
provider_name: Inception
provider_slug: inception
slug: inception-eligibility
source_date: '2026-11-09'
source_filename: inception-eligibility.yml
source_heading: Eligibility
source_page: https://www.inceptionlabs.ai/docs/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inception\naid: inception\nurl: https://www.inceptionlabs.ai/docs/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not export or provide access to the Services into any U.S. embargoed countries or to anyone on (i)\n    the U.S. Treasury Department’s list of Specially Designated Nationals\nentity_types:\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you\
  \ are authorized to agree to these Terms on that organization’s or entity’s behalf\nrestricted_uses:\n- summary: High-stakes decisions affecting individual rights\n  text: relates to high-stakes decision making involving individual rights\n- summary: Political campaign content\n  text: generates political campaign content\n- summary: Misinformation\n  text: generates or spreads misinformation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent and warrant that you are an individual of legal age to form a binding contract (or if not,\n    you’ve received your parent’s or guardian’s permission to use the Services\n"
source_yaml_url: https://artifacts.apis.io/inception/eligibility/inception-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Inception's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Diffusion Models
- Code Completion
- Machine Learning
- Developer Tools
- Foundation Models
---
