---
api_specs:
- filename: cleolm-com-tools-api-openapi.yml
  format: yaml
  label: CleoLM Tools API
  slug: cleolm-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cleolm-com/openapi/cleolm-com-tools-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years of age (or 16 years of age if you are located in the European Union or United Kingdom) to use the Service.
    type: individual
  - text: If you are using the Service on behalf of a company, organization, or other entity, you represent and warrant that you have the authority to bind such entity to these Terms
    type: business
  minimum_age:
    text: You must be at least 13 years of age (or 16 years of age if you are located in the European Union or United Kingdom) to use the Service.
    value: '13'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: Use the Service for any illegal purpose or to violate any applicable laws or regulations
  - summary: Unauthorized content processing
    text: Submit URLs to private or restricted videos without authorization
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
name: CleoLM
provenance_date: '2026-11-09'
provider_name: CleoLM
provider_slug: cleolm-com
slug: cleolm-com-eligibility
source_date: '2026-11-09'
source_filename: cleolm-com-eligibility.yml
source_heading: Eligibility
source_page: https://cleolm.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CleoLM\naid: cleolm-com\nurl: https://cleolm.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age (or 16 years of age if you are located in the European Union or United\n    Kingdom) to use the Service.\n- type: business\n  text: If you are using the Service on behalf of a company, organization, or other entity, you represent and warrant\n    that you have the authority to bind such entity to these Terms\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: Use the Service for any\
  \ illegal purpose or to violate any applicable laws or regulations\n- summary: Unauthorized content processing\n  text: Submit URLs to private or restricted videos without authorization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age (or 16 years of age if you are located in the European Union or United\n    Kingdom) to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/cleolm-com/eligibility/cleolm-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CleoLM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Transcription
- Podcasts
- YouTube
- Search
- MCP
- Video
---
