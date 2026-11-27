---
api_specs:
- filename: askai-openapi-generated.yml
  format: yaml
  label: AskAI API
  slug: askai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askai/openapi/_ae-authored/askai-openapi-generated.yml
- filename: askai-gptfy-api-api-openapi.yml
  format: yaml
  label: GPTfy GPTfy API
  slug: askai-gptfy-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askai/openapi/askai-gptfy-api-api-openapi.yml
- filename: askai-chat-completions-api-openapi.yml
  format: yaml
  label: GPTfy Chat Completions API
  slug: askai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/askai/openapi/askai-chat-completions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The term "you" or "your" refers to the individual or entity accessing or using the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Sexual or degrading imagery of real people
    text: to create sexual, intimate, nude, or otherwise degrading imagery of a real person
  - summary: Sexual or exploitative content involving minors
    text: Produce sexual, intimate, nude, or otherwise degrading imagery of any real person, or any sexual or exploitative content depicting a minor.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The Service is offered free of charge and generally does not require user registration for basic access.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GPTfy
provenance_date: '2026-11-09'
provider_name: GPTfy
provider_slug: askai
slug: askai-eligibility
source_date: '2026-11-09'
source_filename: askai-eligibility.yml
source_heading: Eligibility
source_page: https://askai.free/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GPTfy\naid: askai\nurl: https://askai.free/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The term \"you\" or \"your\" refers to the individual or entity accessing or using the Service.\nrestricted_uses:\n- summary: Sexual or degrading imagery of real people\n  text: to create sexual, intimate, nude, or otherwise degrading imagery of a real person\n- summary: Sexual or exploitative content involving minors\n  text: Produce sexual, intimate, nude, or otherwise degrading imagery of any real person, or any sexual or\
  \ exploitative\n    content depicting a minor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The Service is offered free of charge and generally does not require user registration for basic access.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/askai/eligibility/askai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from GPTfy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Language-Model
- Platform
---
