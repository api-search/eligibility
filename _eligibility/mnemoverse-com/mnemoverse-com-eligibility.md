---
api_specs:
- filename: mnemoverse-com-health-api-openapi.yml
  format: yaml
  label: Mnemoverse Health API
  slug: mnemoverse-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mnemoverse-com/openapi/mnemoverse-com-health-api-openapi.yml
- filename: mnemoverse-com-memory-api-openapi.yml
  format: yaml
  label: Mnemoverse Memory API
  slug: mnemoverse-com-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mnemoverse-com/openapi/mnemoverse-com-memory-api-openapi.yml
- filename: mnemoverse-com-memory-v1-api-openapi.yml
  format: yaml
  label: Mnemoverse Memory V1 API
  slug: mnemoverse-com-memory-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mnemoverse-com/openapi/mnemoverse-com-memory-v1-api-openapi.yml
- filename: mnemoverse-com-vault-api-openapi.yml
  format: yaml
  label: Mnemoverse Vault API
  slug: mnemoverse-com-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mnemoverse-com/openapi/mnemoverse-com-vault-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service for a company or other organization, you accept these Terms for it and confirm you are authorized to do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful content or activity
    text: use the service for unlawful content or activity
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
name: Mnemoverse
provenance_date: '2026-11-10'
provider_name: Mnemoverse
provider_slug: mnemoverse-com
slug: mnemoverse-com-eligibility
source_date: '2026-11-10'
source_filename: mnemoverse-com-eligibility.yml
source_heading: Eligibility
source_page: https://mnemoverse.com/docs/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mnemoverse\naid: mnemoverse-com\nurl: https://mnemoverse.com/docs/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service for a company or other organization, you accept these Terms for it and confirm you\n    are authorized to do so.\nrestricted_uses:\n- summary: Unlawful content or activity\n  text: use the service for unlawful content or activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mnemoverse-com/eligibility/mnemoverse-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Mnemoverse's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Persistent
---
