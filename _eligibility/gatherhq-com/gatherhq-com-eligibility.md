---
api_specs:
- filename: gatherhq-com-agents-api-openapi.yml
  format: yaml
  label: Gather Agents API
  slug: gatherhq-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-agents-api-openapi.yml
- filename: gatherhq-com-dimensions-api-openapi.yml
  format: yaml
  label: Gather Dimensions API
  slug: gatherhq-com-dimensions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-dimensions-api-openapi.yml
- filename: gatherhq-com-health-api-openapi.yml
  format: yaml
  label: Gather Health API
  slug: gatherhq-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-health-api-openapi.yml
- filename: gatherhq-com-mcp-api-openapi.yml
  format: yaml
  label: Gather MCP API
  slug: gatherhq-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-mcp-api-openapi.yml
- filename: gatherhq-com-questions-api-openapi.yml
  format: yaml
  label: Gather Questions API
  slug: gatherhq-com-questions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-questions-api-openapi.yml
- filename: gatherhq-com-reviews-api-openapi.yml
  format: yaml
  label: Gather Reviews API
  slug: gatherhq-com-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-reviews-api-openapi.yml
- filename: gatherhq-com-sources-api-openapi.yml
  format: yaml
  label: Gather Sources API
  slug: gatherhq-com-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-sources-api-openapi.yml
- filename: gatherhq-com-stats-api-openapi.yml
  format: yaml
  label: Gather Stats API
  slug: gatherhq-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-stats-api-openapi.yml
- filename: gatherhq-com-tools-api-openapi.yml
  format: yaml
  label: Gather Tools API
  slug: gatherhq-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gatherhq-com/openapi/gatherhq-com-tools-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Gather is an AI-moderated market research platform offered to businesses ("Customers")
    type: business
  - text: You represent and warrant that you are an individual of legal age to form a binding contract.
    type: individual
  minimum_age:
    text: You represent and warrant that you are an individual of legal age to form a binding contract.
    value: legal age to form a binding contract
  restricted_uses:
  - summary: Unlawful, harmful or fraudulent use
    text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise objectionable
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
name: Gather
provenance_date: '2026-11-09'
provider_name: Gather
provider_slug: gatherhq-com
slug: gatherhq-com-eligibility
source_date: '2026-11-09'
source_filename: gatherhq-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.gatherhq.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gather\naid: gatherhq-com\nurl: https://www.gatherhq.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Gather is an AI-moderated market research platform offered to businesses (\"Customers\")\n- type: individual\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\nrestricted_uses:\n- summary: Unlawful, harmful or fraudulent use\n  text: is dangerous, harmful, fraudulent, deceptive, threatening, harassing, defamatory, obscene, or otherwise\n    objectionable\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age to form a binding contract\n  text: You represent and warrant that you are an individual of legal age to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/gatherhq-com/eligibility/gatherhq-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Gather's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Buyer Intelligence
- Market Research
- GTM-Tools
- Software-as-a-Service
---
