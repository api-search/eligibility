---
api_specs:
- filename: decionis-com-well-known-openapi.json
  format: json
  label: Decionis Policy Evaluation API .well-known API
  slug: decionis-policy-evaluation-api-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decionis-com/openapi/_original/decionis-com-well-known-openapi.json
- filename: decionis-com-openapi-openapi.yml
  format: yaml
  label: Decionis Vertex Extension Verify API Openapi API
  slug: decionis-vertex-extension-verify-api-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decionis-com/openapi/_original/decionis-com-openapi-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these terms on behalf of a company or other legal entity, you represent that you have the authority to bind such entity to these terms.
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
name: decionis-com
provenance_date: '2026-11-09'
provider_name: decionis-com
provider_slug: decionis-com
slug: decionis-com-eligibility
source_date: '2026-11-09'
source_filename: decionis-com-eligibility.yml
source_heading: Eligibility
source_page: https://decionis.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: decionis-com\naid: decionis-com\nurl: https://decionis.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these terms on behalf of a company or other legal entity, you represent that you have\n    the authority to bind such entity to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/decionis-com/eligibility/decionis-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from decionis-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Decision-Making
- Enterprise
- Automation
- Finance
---
