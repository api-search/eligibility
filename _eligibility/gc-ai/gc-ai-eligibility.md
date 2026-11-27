---
api_specs:
- filename: gc-ai-chat-api-openapi.yml
  format: yaml
  label: GC AI Chat API
  slug: gc-ai-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-chat-api-openapi.yml
- filename: gc-ai-files-api-openapi.yml
  format: yaml
  label: GC AI Files API
  slug: gc-ai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-files-api-openapi.yml
- filename: gc-ai-folders-api-openapi.yml
  format: yaml
  label: GC AI Folders API
  slug: gc-ai-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-folders-api-openapi.yml
- filename: gc-ai-playbooks-api-openapi.yml
  format: yaml
  label: GC AI Playbooks API
  slug: gc-ai-playbooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-playbooks-api-openapi.yml
- filename: gc-ai-profiles-api-openapi.yml
  format: yaml
  label: GC AI Profiles API
  slug: gc-ai-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-profiles-api-openapi.yml
- filename: gc-ai-projects-api-openapi.yml
  format: yaml
  label: GC AI Projects API
  slug: gc-ai-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-projects-api-openapi.yml
- filename: gc-ai-skills-api-openapi.yml
  format: yaml
  label: GC AI Skills API
  slug: gc-ai-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-skills-api-openapi.yml
- filename: gc-ai-usage-api-openapi.yml
  format: yaml
  label: GC AI Usage API
  slug: gc-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-usage-api-openapi.yml
- filename: gc-ai-utility-api-openapi.yml
  format: yaml
  label: GC AI Utility API
  slug: gc-ai-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gc-ai/openapi/gc-ai-utility-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Section 12.3 prohibits use in any U.S embargoed country or region, but no countries are named as served or excluded.
  entity_types:
  - text: These terms apply to self-serve purchases and individual plans only
    type: individual
  - text: If you access or use the Service on behalf of an entity (a “Company”), you represent and warrant that you have the authority to bind the Company to the terms of the Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited AI practices
    text: you shall not use the Platform for any purpose classified as a “prohibited AI practice” under Article 5 of the EU AI Act.
  - summary: Sensitive regulated data
    text: Provide any personally identifiable health data, payment card industry data, classified information or data subject to the International Traffic in Arms Regulations
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
name: GC AI
provenance_date: '2026-11-09'
provider_name: GC AI
provider_slug: gc-ai
slug: gc-ai-eligibility
source_date: '2026-11-09'
source_filename: gc-ai-eligibility.yml
source_heading: Eligibility
source_page: https://gc.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GC AI\naid: gc-ai\nurl: https://gc.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Section 12.3 prohibits use in any U.S embargoed country or region, but no countries are named as served\n    or excluded.\nentity_types:\n- type: individual\n  text: These terms apply to self-serve purchases and individual plans only\n- type: business\n  text: If you access or use the Service on behalf of an entity (a “Company”), you represent and warrant that you\n    have the authority to bind the Company to the terms of the Agreement\nrestricted_uses:\n- summary: Prohibited AI practices\n\
  \  text: you shall not use the Platform for any purpose classified as a “prohibited AI practice” under Article 5\n    of the EU AI Act.\n- summary: Sensitive regulated data\n  text: Provide any personally identifiable health data, payment card industry data, classified information or data\n    subject to the International Traffic in Arms Regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gc-ai/eligibility/gc-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 5 quoted statements, read from GC AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Legal
- Legal AI
- Contracts
- In-House Counsel
- Artificial Intelligence
- Document Review
- Enterprise
- MCP
---
