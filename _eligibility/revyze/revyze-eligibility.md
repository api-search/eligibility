---
api_specs:
- filename: revyze-admin-api-openapi.yml
  format: yaml
  label: Revyze Admin API
  slug: revyze-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-admin-api-openapi.yml
- filename: revyze-coach-api-openapi.yml
  format: yaml
  label: Revyze Coach API
  slug: revyze-coach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-coach-api-openapi.yml
- filename: revyze-fastapi-api-openapi.yml
  format: yaml
  label: Revyze FastAPI API
  slug: revyze-fastapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-fastapi-api-openapi.yml
- filename: revyze-force-upgrade-app-api-openapi.yml
  format: yaml
  label: Revyze Force Upgrade App API
  slug: revyze-force-upgrade-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-force-upgrade-app-api-openapi.yml
- filename: revyze-graphql3-api-openapi.yml
  format: yaml
  label: Revyze Graphql3 API
  slug: revyze-graphql3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-graphql3-api-openapi.yml
- filename: revyze-health-api-openapi.yml
  format: yaml
  label: Revyze Health API
  slug: revyze-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-health-api-openapi.yml
- filename: revyze-multiplayer-api-openapi.yml
  format: yaml
  label: Revyze Multiplayer API
  slug: revyze-multiplayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-multiplayer-api-openapi.yml
- filename: revyze-privacy-policy-api-openapi.yml
  format: yaml
  label: Revyze Privacy Policy API
  slug: revyze-privacy-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-privacy-policy-api-openapi.yml
- filename: revyze-privacy-policy-en-api-openapi.yml
  format: yaml
  label: Revyze Privacy Policy En API
  slug: revyze-privacy-policy-en-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-privacy-policy-en-api-openapi.yml
- filename: revyze-webhook-api-openapi.yml
  format: yaml
  label: Revyze Webhook API
  slug: revyze-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revyze/openapi/revyze-webhook-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Les achats de services payants sont réservés aux personnes majeures ou aux mineurs ayant obtenu l'autorisation préalable de leurs représentants légaux.
    type: individual
  minimum_age:
    text: Pour publier du contenu sur Revyze, tu dois avoir au moins 13 ans.
    value: '13'
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
name: Revyze
provenance_date: '2026-11-10'
provider_name: Revyze
provider_slug: revyze
slug: revyze-eligibility
source_date: '2026-11-10'
source_filename: revyze-eligibility.yml
source_heading: Eligibility
source_page: https://api.revyze.fr/privacy_policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revyze\naid: revyze\nurl: https://api.revyze.fr/privacy_policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Les achats de services payants sont réservés aux personnes majeures ou aux mineurs ayant obtenu l'autorisation\n    préalable de leurs représentants légaux.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Pour publier du contenu sur Revyze, tu dois avoir au moins 13 ans.\n"
source_yaml_url: https://artifacts.apis.io/revyze/eligibility/revyze-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Revyze's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EdTech
- Education
- Mobile
- Video
- Learning
- Quiz
- France
- GraphQL
---
