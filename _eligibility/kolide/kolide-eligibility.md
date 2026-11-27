---
api_specs:
- filename: kolide-admin-users-api-openapi.yml
  format: yaml
  label: Kolide Admin Users API
  slug: kolide-admin-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-admin-users-api-openapi.yml
- filename: kolide-audit-logs-api-openapi.yml
  format: yaml
  label: Kolide Audit Logs API
  slug: kolide-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-audit-logs-api-openapi.yml
- filename: kolide-auth-logs-api-openapi.yml
  format: yaml
  label: Kolide Auth Logs API
  slug: kolide-auth-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-auth-logs-api-openapi.yml
- filename: kolide-checks-api-openapi.yml
  format: yaml
  label: Kolide Checks API
  slug: kolide-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-checks-api-openapi.yml
- filename: kolide-custom-check-drafts-api-openapi.yml
  format: yaml
  label: Kolide Custom Check Drafts API
  slug: kolide-custom-check-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-custom-check-drafts-api-openapi.yml
- filename: kolide-deprovisioned-people-api-openapi.yml
  format: yaml
  label: Kolide Deprovisioned People API
  slug: kolide-deprovisioned-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-deprovisioned-people-api-openapi.yml
- filename: kolide-device-groups-api-openapi.yml
  format: yaml
  label: Kolide Device Groups API
  slug: kolide-device-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-device-groups-api-openapi.yml
- filename: kolide-devices-api-openapi.yml
  format: yaml
  label: Kolide Devices API
  slug: kolide-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-devices-api-openapi.yml
- filename: kolide-exemption-requests-api-openapi.yml
  format: yaml
  label: Kolide Exemption Requests API
  slug: kolide-exemption-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-exemption-requests-api-openapi.yml
- filename: kolide-issues-api-openapi.yml
  format: yaml
  label: Kolide Issues API
  slug: kolide-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-issues-api-openapi.yml
- filename: kolide-live-query-campaigns-api-openapi.yml
  format: yaml
  label: Kolide Live Query Campaigns API
  slug: kolide-live-query-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-live-query-campaigns-api-openapi.yml
- filename: kolide-packages-api-openapi.yml
  format: yaml
  label: Kolide Packages API
  slug: kolide-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-packages-api-openapi.yml
- filename: kolide-people-api-openapi.yml
  format: yaml
  label: Kolide People API
  slug: kolide-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-people-api-openapi.yml
- filename: kolide-person-groups-api-openapi.yml
  format: yaml
  label: Kolide Person Groups API
  slug: kolide-person-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-person-groups-api-openapi.yml
- filename: kolide-registration-requests-api-openapi.yml
  format: yaml
  label: Kolide Registration Requests API
  slug: kolide-registration-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-registration-requests-api-openapi.yml
- filename: kolide-reporting-api-openapi.yml
  format: yaml
  label: Kolide Reporting API
  slug: kolide-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-reporting-api-openapi.yml
- filename: kolide-whoami-api-openapi.yml
  format: yaml
  label: Kolide Whoami API
  slug: kolide-whoami-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolide/openapi/kolide-whoami-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THE AGREEMENT ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE FULL AUTHORITY TO BIND THE CUSTOMER
    type: business
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT INDIVIDUALLY, YOU REPRESENT AND WARRANT
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export and sanctions compliance
    text: Customer will comply with all United States and foreign export and import laws, rules, and regulations related to Customer’s use of any Services outside the United States.
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
name: Kolide
provenance_date: '2026-11-09'
provider_name: Kolide
provider_slug: kolide
slug: kolide-eligibility
source_date: '2026-11-09'
source_filename: kolide-eligibility.yml
source_heading: Eligibility
source_page: https://www.kolide.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kolide\naid: kolide\nurl: https://www.kolide.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THE AGREEMENT ON BEHALF OF A LEGAL ENTITY, YOU REPRESENT AND WARRANT THAT YOU HAVE\n    FULL AUTHORITY TO BIND THE CUSTOMER\n- type: individual\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT INDIVIDUALLY, YOU REPRESENT AND WARRANT\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: Customer will comply with all United States and foreign export and import laws, rules, and regulations\
  \ related\n    to Customer’s use of any Services outside the United States.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kolide/eligibility/kolide-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Kolide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- B2B
- Security
- Device Trust
- Endpoint Security
- Zero Trust
- Compliance
- Identity
- osquery
- Device Management
---
