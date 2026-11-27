---
api_specs:
- filename: unbrowse-ai-account-api-openapi.yml
  format: yaml
  label: unbrowse-ai Account API
  slug: unbrowse-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-account-api-openapi.yml
- filename: unbrowse-ai-apps-tools-api-openapi.yml
  format: yaml
  label: unbrowse-ai Apps & tools API
  slug: unbrowse-ai-apps-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-apps-tools-api-openapi.yml
- filename: unbrowse-ai-capabilities-api-openapi.yml
  format: yaml
  label: unbrowse-ai Capabilities API
  slug: unbrowse-ai-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-capabilities-api-openapi.yml
- filename: unbrowse-ai-connected-apps-api-openapi.yml
  format: yaml
  label: unbrowse-ai Connected apps API
  slug: unbrowse-ai-connected-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-connected-apps-api-openapi.yml
- filename: unbrowse-ai-indexing-api-openapi.yml
  format: yaml
  label: unbrowse-ai Indexing API
  slug: unbrowse-ai-indexing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-indexing-api-openapi.yml
- filename: unbrowse-ai-learning-api-openapi.yml
  format: yaml
  label: unbrowse-ai Learning API
  slug: unbrowse-ai-learning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-learning-api-openapi.yml
- filename: unbrowse-ai-logins-vault-api-openapi.yml
  format: yaml
  label: unbrowse-ai Logins & vault API
  slug: unbrowse-ai-logins-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-logins-vault-api-openapi.yml
- filename: unbrowse-ai-marketplace-api-openapi.yml
  format: yaml
  label: unbrowse-ai Marketplace API
  slug: unbrowse-ai-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-marketplace-api-openapi.yml
- filename: unbrowse-ai-orgs-api-openapi.yml
  format: yaml
  label: unbrowse-ai Orgs API
  slug: unbrowse-ai-orgs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-orgs-api-openapi.yml
- filename: unbrowse-ai-pages-api-openapi.yml
  format: yaml
  label: unbrowse-ai Pages API
  slug: unbrowse-ai-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-pages-api-openapi.yml
- filename: unbrowse-ai-replays-api-openapi.yml
  format: yaml
  label: unbrowse-ai Replays API
  slug: unbrowse-ai-replays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-replays-api-openapi.yml
- filename: unbrowse-ai-runs-api-openapi.yml
  format: yaml
  label: unbrowse-ai Runs API
  slug: unbrowse-ai-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-runs-api-openapi.yml
- filename: unbrowse-ai-saved-queries-api-openapi.yml
  format: yaml
  label: unbrowse-ai Saved queries API
  slug: unbrowse-ai-saved-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-saved-queries-api-openapi.yml
- filename: unbrowse-ai-sites-api-openapi.yml
  format: yaml
  label: unbrowse-ai Sites API
  slug: unbrowse-ai-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unbrowse-ai/openapi/unbrowse-ai-sites-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old.
    type: individual
  - text: if you use it for an organisation, you confirm you may bind that organisation.
    type: business
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
  restricted_uses:
  - summary: Unlawful or unauthorised activity
    text: 'You must not use the Service to: access systems or accounts you are not authorised to access'
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
name: unbrowse-ai
provenance_date: '2026-11-10'
provider_name: unbrowse-ai
provider_slug: unbrowse-ai
slug: unbrowse-ai-eligibility
source_date: '2026-11-10'
source_filename: unbrowse-ai-eligibility.yml
source_heading: Eligibility
source_page: https://unbrowse.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: unbrowse-ai\naid: unbrowse-ai\nurl: https://unbrowse.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old.\n- type: business\n  text: if you use it for an organisation, you confirm you may bind that organisation.\nrestricted_uses:\n- summary: Unlawful or unauthorised activity\n  text: 'You must not use the Service to: access systems or accounts you are not authorised to access'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text:\
  \ You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/unbrowse-ai/eligibility/unbrowse-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from unbrowse-ai's own page on 2026-11-10.
synthetic: false
tags:
- AI Agents
- Developer Tools
---
