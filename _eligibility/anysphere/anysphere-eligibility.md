---
api_specs:
- filename: anysphere-agents-api-openapi.yml
  format: yaml
  label: Anysphere Agents API
  slug: anysphere-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-agents-api-openapi.yml
- filename: anysphere-me-api-openapi.yml
  format: yaml
  label: Anysphere Me API
  slug: anysphere-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-me-api-openapi.yml
- filename: anysphere-models-api-openapi.yml
  format: yaml
  label: Anysphere Models API
  slug: anysphere-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-models-api-openapi.yml
- filename: anysphere-repositories-api-openapi.yml
  format: yaml
  label: Anysphere Repositories API
  slug: anysphere-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-repositories-api-openapi.yml
- filename: anysphere-sub-tokens-api-openapi.yml
  format: yaml
  label: Anysphere Sub Tokens API
  slug: anysphere-sub-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anysphere/openapi/anysphere-sub-tokens-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service may not be used in or for the benefit of, or exported or re-exported to (a) any U.S. embargoed country or territory or (b) any individual or entity with whom dealings are prohibited or restricted under applicable trade laws.
  entity_types:
  - text: You must be at least the age of majority in your jurisdiction (e.g., 18 years old in the United States) or 18 years old, whichever is higher, to use the Service.
    type: individual
  - text: If you are using the Service as part of your work for a company or organization that has a Master Services Agreement (“ MSA ”) with Anysphere, your use of the Service is governed by that MSA.
    type: business
  minimum_age:
    text: you are at least 18 years old or the age of majority in your jurisdiction, whichever is higher
    value: '18'
  restricted_uses:
  - summary: No sensitive regulated data
    text: (x) send or otherwise provide to Anysphere data or information that is subject to specific protections under applicable laws beyond any requirements that apply to "personal information" or "personal data" generally
  - summary: Export and trade control restrictions
    text: Our Service may not be used for any end use prohibited by applicable trade laws, and your Input may not include material or information that requires a government license for release or export.
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
name: Anysphere
provenance_date: '2026-11-09'
provider_name: Anysphere
provider_slug: anysphere
slug: anysphere-eligibility
source_date: '2026-11-09'
source_filename: anysphere-eligibility.yml
source_heading: Eligibility
source_page: https://cursor.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anysphere\naid: anysphere\nurl: https://cursor.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service may not be used in or for the benefit of, or exported or re-exported to (a) any U.S. embargoed\n    country or territory or (b) any individual or entity with whom dealings are prohibited or restricted under applicable\n    trade laws.\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your jurisdiction (e.g., 18 years old in the United States)\n    or 18 years old, whichever is higher, to use the Service.\n\
  - type: business\n  text: If you are using the Service as part of your work for a company or organization that has a Master Services\n    Agreement (“ MSA ”) with Anysphere, your use of the Service is governed by that MSA.\nrestricted_uses:\n- summary: No sensitive regulated data\n  text: (x) send or otherwise provide to Anysphere data or information that is subject to specific protections under\n    applicable laws beyond any requirements that apply to \"personal information\" or \"personal data\" generally\n- summary: Export and trade control restrictions\n  text: Our Service may not be used for any end use prohibited by applicable trade laws, and your Input may not\n    include material or information that requires a government license for release or export.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old or the age of majority in your jurisdiction, whichever is higher\n"
source_yaml_url: https://artifacts.apis.io/anysphere/eligibility/anysphere-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Anysphere's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Artificial Intelligence
- Code Editor
- Coding Agents
- Cloud Agents
- Developer Productivity
- IDE
---
