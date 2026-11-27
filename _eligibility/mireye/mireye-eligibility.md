---
api_specs:
- filename: mireye-ask-api-openapi.yml
  format: yaml
  label: Mireye Ask API
  slug: mireye-ask-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-ask-api-openapi.yml
- filename: mireye-ask-site-api-openapi.yml
  format: yaml
  label: Mireye Ask Site API
  slug: mireye-ask-site-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-ask-site-api-openapi.yml
- filename: mireye-auth-api-openapi.yml
  format: yaml
  label: Mireye Auth API
  slug: mireye-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-auth-api-openapi.yml
- filename: mireye-authorize-api-openapi.yml
  format: yaml
  label: Mireye Authorize API
  slug: mireye-authorize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-authorize-api-openapi.yml
- filename: mireye-feature-requests-api-openapi.yml
  format: yaml
  label: Mireye Feature Requests API
  slug: mireye-feature-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-feature-requests-api-openapi.yml
- filename: mireye-fetch-api-openapi.yml
  format: yaml
  label: Mireye Fetch API
  slug: mireye-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-fetch-api-openapi.yml
- filename: mireye-healthz-api-openapi.yml
  format: yaml
  label: Mireye Healthz API
  slug: mireye-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-healthz-api-openapi.yml
- filename: mireye-mcp-api-openapi.yml
  format: yaml
  label: Mireye Mcp API
  slug: mireye-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-mcp-api-openapi.yml
- filename: mireye-meta-api-openapi.yml
  format: yaml
  label: Mireye Meta API
  slug: mireye-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-meta-api-openapi.yml
- filename: mireye-readyz-api-openapi.yml
  format: yaml
  label: Mireye Readyz API
  slug: mireye-readyz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-readyz-api-openapi.yml
- filename: mireye-register-api-openapi.yml
  format: yaml
  label: Mireye Register API
  slug: mireye-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-register-api-openapi.yml
- filename: mireye-revoke-api-openapi.yml
  format: yaml
  label: Mireye Revoke API
  slug: mireye-revoke-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-revoke-api-openapi.yml
- filename: mireye-sites-api-openapi.yml
  format: yaml
  label: Mireye Sites API
  slug: mireye-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-sites-api-openapi.yml
- filename: mireye-token-api-openapi.yml
  format: yaml
  label: Mireye Token API
  slug: mireye-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-token-api-openapi.yml
- filename: mireye-users-api-openapi.yml
  format: yaml
  label: Mireye Users API
  slug: mireye-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-users-api-openapi.yml
- filename: mireye-well-known-api-openapi.yml
  format: yaml
  label: Mireye .well Known API
  slug: mireye-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-well-known-api-openapi.yml
- filename: mireye-oauth-api-openapi.yml
  format: yaml
  label: Mireye OAUTH API
  slug: mireye-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mireye/openapi/mireye-oauth-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept for an organization, you represent that you have authority to bind that organization; "you" means that organization.
    type: business
  - text: Otherwise, "you" means you individually.
    type: individual
  minimum_age:
    text: You must be legally able to enter this agreement.
    value: null
  restricted_uses:
  - summary: Licensed data outside permitted scope
    text: 'Except for a use expressly authorized by Mireye in writing within its applicable data rights, you must not: Sell, resell, sublicense, publish, distribute or otherwise make Licensed Property Data available to third parties outside the permitted end-user and recipient scope.'
  - summary: Systematic extraction or reconstruction
    text: Systematically extract, pool or aggregate it to reconstruct a substantial portion of an underlying licensed dataset
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require verified account information, renewed acceptance of material terms, and new or reauthorized credentials before enabling licensed-data features.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mireye
provenance_date: '2026-11-10'
provider_name: Mireye
provider_slug: mireye
slug: mireye-eligibility
source_date: '2026-11-10'
source_filename: mireye-eligibility.yml
source_heading: Eligibility
source_page: https://www.mireye.com/legal/earth/2026-10-20-v1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mireye\naid: mireye\nurl: https://www.mireye.com/legal/earth/2026-10-20-v1\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept for an organization, you represent that you have authority to bind that organization; \"you\"\n    means that organization.\n- type: individual\n  text: Otherwise, \"you\" means you individually.\nrestricted_uses:\n- summary: Licensed data outside permitted scope\n  text: 'Except for a use expressly authorized by Mireye in writing within its applicable data rights, you must\n    not:\
  \ Sell, resell, sublicense, publish, distribute or otherwise make Licensed Property Data available to third\n    parties outside the permitted end-user and recipient scope.'\n- summary: Systematic extraction or reconstruction\n  text: Systematically extract, pool or aggregate it to reconstruct a substantial portion of an underlying licensed\n    dataset\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require verified account information, renewed acceptance of material terms, and new or reauthorized\n    credentials before enabling licensed-data features.\nminimum_age:\n  value: null\n  text: You must be legally able to enter this agreement.\n"
source_yaml_url: https://artifacts.apis.io/mireye/eligibility/mireye-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Mireye's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Geospatial
- Geographic Information System
- Location
- AI Agents
- MCP
- Government Data
- Risk Management
- Insurance
- Data
---
