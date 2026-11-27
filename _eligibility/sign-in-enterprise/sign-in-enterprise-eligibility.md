---
api_specs:
- filename: sign-in-enterprise-batches-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Batches API
  slug: sign-in-enterprise-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-batches-api-openapi.yml
- filename: sign-in-enterprise-capacities-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Capacities API
  slug: sign-in-enterprise-capacities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-capacities-api-openapi.yml
- filename: sign-in-enterprise-groupvisits-api-openapi.yml
  format: yaml
  label: Sign In Enterprise GroupVisits API
  slug: sign-in-enterprise-groupvisits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-groupvisits-api-openapi.yml
- filename: sign-in-enterprise-hosts-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Hosts API
  slug: sign-in-enterprise-hosts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-hosts-api-openapi.yml
- filename: sign-in-enterprise-invites-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Invites API
  slug: sign-in-enterprise-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-invites-api-openapi.yml
- filename: sign-in-enterprise-locations-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Locations API
  slug: sign-in-enterprise-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-locations-api-openapi.yml
- filename: sign-in-enterprise-packages-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Packages API
  slug: sign-in-enterprise-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-packages-api-openapi.yml
- filename: sign-in-enterprise-parking-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Parking API
  slug: sign-in-enterprise-parking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-parking-api-openapi.yml
- filename: sign-in-enterprise-registrations-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Registrations API
  slug: sign-in-enterprise-registrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-registrations-api-openapi.yml
- filename: sign-in-enterprise-users-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Users API
  slug: sign-in-enterprise-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-users-api-openapi.yml
- filename: sign-in-enterprise-watchlists-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Watchlists API
  slug: sign-in-enterprise-watchlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-watchlists-api-openapi.yml
- filename: sign-in-enterprise-audit-logs-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Audit Logs API
  slug: sign-in-enterprise-audit-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-audit-logs-api-openapi.yml
- filename: sign-in-enterprise-email-templates-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Email Templates API
  slug: sign-in-enterprise-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-email-templates-api-openapi.yml
- filename: sign-in-enterprise-sign-ins-api-openapi.yml
  format: yaml
  label: Sign In Enterprise Sign Ins API
  slug: sign-in-enterprise-sign-ins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sign-in-enterprise/openapi/sign-in-enterprise-sign-ins-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Export Compliance: You will not permit any Authorized User to access or use any Products in a U.S.-embargoed country or region or in violation of any U.S. export law or regulation.'
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or deceptive marketing or harmful uploads
    text: You shall not (a) use the Products to engage in any deceptive, misleading, illegal or unethical marketing activities
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
name: Sign In Enterprise
provenance_date: '2026-11-10'
provider_name: Sign In Enterprise
provider_slug: sign-in-enterprise
slug: sign-in-enterprise-eligibility
source_date: '2026-11-10'
source_filename: sign-in-enterprise-eligibility.yml
source_heading: Eligibility
source_page: https://signinsolutions.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sign In Enterprise\naid: sign-in-enterprise\nurl: https://signinsolutions.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Export Compliance: You will not permit any Authorized User to access or use any Products in a U.S.-embargoed\n    country or region or in violation of any U.S. export law or regulation.'\nentity_types: []\nrestricted_uses:\n- summary: No unlawful or deceptive marketing or harmful uploads\n  text: You shall not (a) use the Products to engage in any deceptive, misleading, illegal or unethical marketing\n    activities\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sign-in-enterprise/eligibility/sign-in-enterprise-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Sign In Enterprise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Vertical Software
- Visitor Management
- Physical Security
- Workplace Experience
- Identity
- Compliance
- Access Control
---
