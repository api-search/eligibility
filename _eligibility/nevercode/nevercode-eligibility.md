---
api_specs:
- filename: nevercode-app-previews-api-openapi.yml
  format: yaml
  label: Nevercode App Previews API
  slug: nevercode-app-previews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-app-previews-api-openapi.yml
- filename: nevercode-applications-api-openapi.yml
  format: yaml
  label: Nevercode Applications API
  slug: nevercode-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-applications-api-openapi.yml
- filename: nevercode-billing-api-openapi.yml
  format: yaml
  label: Nevercode Billing API
  slug: nevercode-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-billing-api-openapi.yml
- filename: nevercode-build-dashboards-api-openapi.yml
  format: yaml
  label: Nevercode Build Dashboards API
  slug: nevercode-build-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-build-dashboards-api-openapi.yml
- filename: nevercode-builds-api-openapi.yml
  format: yaml
  label: Nevercode Builds API
  slug: nevercode-builds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-builds-api-openapi.yml
- filename: nevercode-meta-api-openapi.yml
  format: yaml
  label: Nevercode Meta API
  slug: nevercode-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-meta-api-openapi.yml
- filename: nevercode-over-the-air-updates-api-openapi.yml
  format: yaml
  label: Nevercode Over-the-air Updates API
  slug: nevercode-over-the-air-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-over-the-air-updates-api-openapi.yml
- filename: nevercode-secrets-and-environment-vars-api-openapi.yml
  format: yaml
  label: Nevercode Secrets and Environment Vars API
  slug: nevercode-secrets-and-environment-vars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-secrets-and-environment-vars-api-openapi.yml
- filename: nevercode-team-invitations-api-openapi.yml
  format: yaml
  label: Nevercode Team Invitations API
  slug: nevercode-team-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-team-invitations-api-openapi.yml
- filename: nevercode-team-members-api-openapi.yml
  format: yaml
  label: Nevercode Team Members API
  slug: nevercode-team-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-team-members-api-openapi.yml
- filename: nevercode-teams-api-openapi.yml
  format: yaml
  label: Nevercode Teams API
  slug: nevercode-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-teams-api-openapi.yml
- filename: nevercode-tester-groups-api-openapi.yml
  format: yaml
  label: Nevercode Tester Groups API
  slug: nevercode-tester-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-tester-groups-api-openapi.yml
- filename: nevercode-users-api-openapi.yml
  format: yaml
  label: Nevercode Users API
  slug: nevercode-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nevercode/openapi/nevercode-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If the Customer is a natural person, then in order to use the Service and enter into the Agreement, the Customer must be at least 18 years of age or have a valid authorization from his or her legal representative or custodian.
    type: individual
  - text: If the Customer is a legal entity, it must be duly incorporated and have full legal capacity
    type: business
  minimum_age:
    text: the Customer must be at least 18 years of age or have a valid authorization from his or her legal representative or custodian.
    value: '18'
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
name: Nevercode
provenance_date: '2026-11-10'
provider_name: Nevercode
provider_slug: nevercode
slug: nevercode-eligibility
source_date: '2026-11-10'
source_filename: nevercode-eligibility.yml
source_heading: Eligibility
source_page: https://codemagic.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nevercode\naid: nevercode\nurl: https://codemagic.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If the Customer is a natural person, then in order to use the Service and enter into the Agreement, the\n    Customer must be at least 18 years of age or have a valid authorization from his or her legal representative\n    or custodian.\n- type: business\n  text: If the Customer is a legal entity, it must be duly incorporated and have full legal capacity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Customer must be at least 18 years of age or have a valid authorization from his or her legal representative\n    or custodian.\n"
source_yaml_url: https://artifacts.apis.io/nevercode/eligibility/nevercode-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Nevercode's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Continuous Integration
- Continuous Delivery
- CI/CD
- DevOps
- Mobile
- Flutter
- Builds
- App Distribution
- Code Signing
- Developer Tools
---
