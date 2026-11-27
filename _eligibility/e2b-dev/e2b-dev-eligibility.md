---
api_specs:
- filename: e2b-dev-events-api-openapi.yml
  format: yaml
  label: E2B Events API
  slug: e2b-dev-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-events-api-openapi.yml
- filename: e2b-dev-sandboxes-api-openapi.yml
  format: yaml
  label: E2B Sandboxes API
  slug: e2b-dev-sandboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-sandboxes-api-openapi.yml
- filename: e2b-dev-tags-api-openapi.yml
  format: yaml
  label: E2B Tags API
  slug: e2b-dev-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-tags-api-openapi.yml
- filename: e2b-dev-templates-api-openapi.yml
  format: yaml
  label: E2B Templates API
  slug: e2b-dev-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-templates-api-openapi.yml
- filename: e2b-dev-volumes-api-openapi.yml
  format: yaml
  label: E2B Volumes API
  slug: e2b-dev-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-volumes-api-openapi.yml
- filename: e2b-dev-webhooks-api-openapi.yml
  format: yaml
  label: E2B Webhooks API
  slug: e2b-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-webhooks-api-openapi.yml
- filename: e2b-dev-e2b-sandbox-events-and-webhooks-api-api-openapi.yml
  format: yaml
  label: E2B Sandbox Events And Webhooks API
  slug: e2b-dev-e2b-sandbox-events-and-webhooks-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-e2b-sandbox-events-and-webhooks-api-api-openapi.yml
- filename: e2b-dev-envd-api-openapi.yml
  format: yaml
  label: E2B Envd API
  slug: e2b-dev-envd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-envd-api-openapi.yml
- filename: e2b-dev-filesystem-api-openapi.yml
  format: yaml
  label: E2B Filesystem API
  slug: e2b-dev-filesystem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-filesystem-api-openapi.yml
- filename: e2b-dev-process-api-openapi.yml
  format: yaml
  label: E2B Process API
  slug: e2b-dev-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-process-api-openapi.yml
- filename: e2b-dev-secrets-api-openapi.yml
  format: yaml
  label: E2B Secrets API
  slug: e2b-dev-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-secrets-api-openapi.yml
- filename: e2b-dev-teams-api-openapi.yml
  format: yaml
  label: E2B Teams API
  slug: e2b-dev-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/e2b-dev/openapi/e2b-dev-teams-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent that you are at least 18 years old
    type: individual
  - text: you have the legal authority and capacity to agree to these Terms as an individual or on behalf of a company
    type: business
  minimum_age:
    text: you represent that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or harmful materials
    text: Use the Services to transmit, store or publish any harassing, obscene, infringing, or illegal materials or information.
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
name: E2B
provenance_date: '2026-11-09'
provider_name: E2B
provider_slug: e2b-dev
slug: e2b-dev-eligibility
source_date: '2026-11-09'
source_filename: e2b-dev-eligibility.yml
source_heading: Eligibility
source_page: https://e2b.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: E2B\naid: e2b-dev\nurl: https://e2b.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent that you are at least 18 years old\n- type: business\n  text: you have the legal authority and capacity to agree to these Terms as an individual or on behalf of a company\nrestricted_uses:\n- summary: Unlawful or harmful materials\n  text: Use the Services to transmit, store or publish any harassing, obscene, infringing, or illegal materials\n    or information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: you represent that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/e2b-dev/eligibility/e2b-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from E2B's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Code Execution
- Code Interpreter
- Sandbox
- Firecracker
- MicroVM
- Computer Use
- Desktop Sandbox
- Templates
- MCP
- Open Source
---
