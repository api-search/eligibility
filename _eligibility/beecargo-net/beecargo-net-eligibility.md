---
api_specs:
- filename: beecargo-net-agent-api-openapi.yml
  format: yaml
  label: Beecargo Agent API
  slug: beecargo-net-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-agent-api-openapi.yml
- filename: beecargo-net-connect-api-openapi.yml
  format: yaml
  label: Beecargo Connect API
  slug: beecargo-net-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-connect-api-openapi.yml
- filename: beecargo-net-downloads-api-openapi.yml
  format: yaml
  label: Beecargo Downloads API
  slug: beecargo-net-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-downloads-api-openapi.yml
- filename: beecargo-net-files-api-openapi.yml
  format: yaml
  label: Beecargo Files API
  slug: beecargo-net-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-files-api-openapi.yml
- filename: beecargo-net-folders-api-openapi.yml
  format: yaml
  label: Beecargo Folders API
  slug: beecargo-net-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-folders-api-openapi.yml
- filename: beecargo-net-system-api-openapi.yml
  format: yaml
  label: Beecargo System API
  slug: beecargo-net-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beecargo-net/openapi/beecargo-net-system-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Violating Acceptable Use Policy
    text: We may suspend or terminate access if you violate these Terms, our Acceptable Use Policy, or if required for security or legal reasons.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: free accounts (subject to approval via Backstage where required)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Beecargo
provenance_date: '2026-11-09'
provider_name: Beecargo
provider_slug: beecargo-net
slug: beecargo-net-eligibility
source_date: '2026-11-09'
source_filename: beecargo-net-eligibility.yml
source_heading: Eligibility
source_page: https://beecargo.net/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beecargo\naid: beecargo-net\nurl: https://beecargo.net/docs/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization.\nrestricted_uses:\n- summary: Violating Acceptable Use Policy\n  text: We may suspend or terminate access if you violate these Terms, our Acceptable Use Policy, or if required\n    for security or legal reasons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: free accounts\
  \ (subject to approval via Backstage where required)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/beecargo-net/eligibility/beecargo-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Beecargo's own page on 2026-11-09.
synthetic: false
tags:
- File Hosting
- Share Links
- Developers
- Agents
---
