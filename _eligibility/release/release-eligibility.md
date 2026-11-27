---
api_specs:
- filename: release-accounts-api-openapi.yml
  format: yaml
  label: Release Accounts API
  slug: release-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-accounts-api-openapi.yml
- filename: release-apps-api-openapi.yml
  format: yaml
  label: Release Apps API
  slug: release-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-apps-api-openapi.yml
- filename: release-builds-api-openapi.yml
  format: yaml
  label: Release Builds API
  slug: release-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-builds-api-openapi.yml
- filename: release-clusters-api-openapi.yml
  format: yaml
  label: Release Clusters API
  slug: release-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-clusters-api-openapi.yml
- filename: release-configs-api-openapi.yml
  format: yaml
  label: Release Configs API
  slug: release-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-configs-api-openapi.yml
- filename: release-deploys-api-openapi.yml
  format: yaml
  label: Release Deploys API
  slug: release-deploys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-deploys-api-openapi.yml
- filename: release-environments-api-openapi.yml
  format: yaml
  label: Release Environments API
  slug: release-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-environments-api-openapi.yml
- filename: release-instances-api-openapi.yml
  format: yaml
  label: Release Instances API
  slug: release-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-instances-api-openapi.yml
- filename: release-remote-development-api-openapi.yml
  format: yaml
  label: Release Remote Development API
  slug: release-remote-development-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/release/openapi/release-remote-development-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is intended for access and use by individuals age 18 or older.
    type: individual
  minimum_age:
    text: The Site is intended for access and use by individuals age 18 or older.
    value: '18'
  restricted_uses:
  - summary: No PHI/HIPAA data
    text: Licensee is prohibited from providing any patient, medical or other protected health information regulated by the Health Information Portability and Accountability Act of 1996
  - summary: Export restrictions
    text: Licensee shall not transfer, export or re-export, directly or indirectly, the Services to any Prohibited Entity
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
name: Release
provenance_date: '2026-11-10'
provider_name: Release
provider_slug: release
slug: release-eligibility
source_date: '2026-11-10'
source_filename: release-eligibility.yml
source_heading: Eligibility
source_page: https://release.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Release\naid: release\nurl: https://release.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is intended for access and use by individuals age 18 or older.\nrestricted_uses:\n- summary: No PHI/HIPAA data\n  text: Licensee is prohibited from providing any patient, medical or other protected health information regulated\n    by the Health Information Portability and Accountability Act of 1996\n- summary: Export restrictions\n  text: Licensee shall not transfer, export or re-export, directly or indirectly,\
  \ the Services to any Prohibited\n    Entity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for access and use by individuals age 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/release/eligibility/release-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Release's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Tools
- Ephemeral Environments
- Platform Engineering
- Deployment
- Kubernetes
- Environments as a Service
- DevOps
- CI/CD
- AI Sandbox
---
