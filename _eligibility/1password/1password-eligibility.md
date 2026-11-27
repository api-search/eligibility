---
api_specs:
- filename: 1password-accounts-api-openapi.yml
  format: yaml
  label: 1Password Accounts API
  slug: 1password-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-accounts-api-openapi.yml
- filename: 1password-activity-api-openapi.yml
  format: yaml
  label: 1Password Activity API
  slug: 1password-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-activity-api-openapi.yml
- filename: 1password-audit-events-api-openapi.yml
  format: yaml
  label: 1Password Audit Events API
  slug: 1password-audit-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-audit-events-api-openapi.yml
- filename: 1password-files-api-openapi.yml
  format: yaml
  label: 1Password Files API
  slug: 1password-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-files-api-openapi.yml
- filename: 1password-health-api-openapi.yml
  format: yaml
  label: 1Password Health API
  slug: 1password-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-health-api-openapi.yml
- filename: 1password-introspection-api-openapi.yml
  format: yaml
  label: 1Password Introspection API
  slug: 1password-introspection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-introspection-api-openapi.yml
- filename: 1password-item-usages-api-openapi.yml
  format: yaml
  label: 1Password Item Usages API
  slug: 1password-item-usages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-item-usages-api-openapi.yml
- filename: 1password-items-api-openapi.yml
  format: yaml
  label: 1Password Items API
  slug: 1password-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-items-api-openapi.yml
- filename: 1password-metrics-api-openapi.yml
  format: yaml
  label: 1Password Metrics API
  slug: 1password-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-metrics-api-openapi.yml
- filename: 1password-sign-in-attempts-api-openapi.yml
  format: yaml
  label: 1Password Sign-In Attempts API
  slug: 1password-sign-in-attempts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-sign-in-attempts-api-openapi.yml
- filename: 1password-vaults-api-openapi.yml
  format: yaml
  label: 1Password Vaults API
  slug: 1password-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-vaults-api-openapi.yml
- filename: 1password-applications-api-openapi.yml
  format: yaml
  label: 1Password Applications API
  slug: 1password-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-applications-api-openapi.yml
- filename: 1password-audit-log-api-openapi.yml
  format: yaml
  label: 1Password Audit log API
  slug: 1password-audit-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-audit-log-api-openapi.yml
- filename: 1password-authentication-api-openapi.yml
  format: yaml
  label: 1Password Authentication API
  slug: 1password-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-authentication-api-openapi.yml
- filename: 1password-contracts-api-openapi.yml
  format: yaml
  label: 1Password Contracts API
  slug: 1password-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-contracts-api-openapi.yml
- filename: 1password-devices-api-openapi.yml
  format: yaml
  label: 1Password Devices API
  slug: 1password-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-devices-api-openapi.yml
- filename: 1password-people-api-openapi.yml
  format: yaml
  label: 1Password People API
  slug: 1password-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-people-api-openapi.yml
- filename: 1password-scim-api-openapi.yml
  format: yaml
  label: 1Password SCIM API
  slug: 1password-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-scim-api-openapi.yml
- filename: 1password-teams-api-openapi.yml
  format: yaml
  label: 1Password Teams API
  slug: 1password-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-teams-api-openapi.yml
- filename: 1password-workflows-api-openapi.yml
  format: yaml
  label: 1Password Workflows API
  slug: 1password-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/1password/openapi/1password-workflows-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export compliance
    text: Customer shall not permit Users to access or use Service in violation of any U.S. export embargo, prohibition or restriction.
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
name: 1Password
provenance_date: '2026-11-09'
provider_name: 1Password
provider_slug: 1password
slug: 1password-eligibility
source_date: '2026-11-09'
source_filename: 1password-eligibility.yml
source_heading: Eligibility
source_page: https://1password.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 1Password\naid: 1password\nurl: https://1password.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export compliance\n  text: Customer shall not permit Users to access or use Service in violation of any U.S. export embargo, prohibition\n    or restriction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/1password/eligibility/1password-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from 1Password's own page on 2026-11-09.
synthetic: false
tags:
- Password Manager
- Passwords
- Security
- Secrets
- Canada
---
