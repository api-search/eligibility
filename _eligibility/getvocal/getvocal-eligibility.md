---
api_specs:
- filename: getvocal-contact-api-openapi.yml
  format: yaml
  label: GetVocal Contact API
  slug: getvocal-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-contact-api-openapi.yml
- filename: getvocal-llms-txt-api-openapi.yml
  format: yaml
  label: GetVocal Llms.txt API
  slug: getvocal-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-llms-txt-api-openapi.yml
- filename: getvocal-well-known-api-openapi.yml
  format: yaml
  label: GetVocal .well Known API
  slug: getvocal-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-well-known-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: GetVocal's services are intended for professional clients seeking to engage in a data protection-compliant approach by using GetVocal's services.
    type: business
  minimum_age:
    text: null
    value: null
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
name: GetVocal
provenance_date: '2026-11-09'
provider_name: GetVocal
provider_slug: getvocal
slug: getvocal-eligibility
source_date: '2026-11-09'
source_filename: getvocal-eligibility.yml
source_heading: Eligibility
source_page: https://www.getvocal.ai/legal-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GetVocal\naid: getvocal\nurl: https://www.getvocal.ai/legal-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: GetVocal's services are intended for professional clients seeking to engage in a data protection-compliant\n    approach by using GetVocal's services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getvocal/eligibility/getvocal-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from GetVocal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice AI
- Conversational AI
- Customer Experience
- AI Agents
- Contact Center
- Agent Governance
- MCP
- Agent-Native
---
