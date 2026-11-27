---
api_specs:
- filename: butterflymx-access-groups-api-openapi.yml
  format: yaml
  label: ButterflyMX Access groups API
  slug: butterflymx-access-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-access-groups-api-openapi.yml
- filename: butterflymx-access-logs-api-openapi.yml
  format: yaml
  label: ButterflyMX Access Logs API
  slug: butterflymx-access-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-access-logs-api-openapi.yml
- filename: butterflymx-access-points-api-openapi.yml
  format: yaml
  label: ButterflyMX Access Points API
  slug: butterflymx-access-points-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-access-points-api-openapi.yml
- filename: butterflymx-access-tools-api-openapi.yml
  format: yaml
  label: ButterflyMX Access Tools API
  slug: butterflymx-access-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-access-tools-api-openapi.yml
- filename: butterflymx-building-integrations-api-openapi.yml
  format: yaml
  label: ButterflyMX Building Integrations API
  slug: butterflymx-building-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-building-integrations-api-openapi.yml
- filename: butterflymx-buildings-api-openapi.yml
  format: yaml
  label: ButterflyMX Buildings API
  slug: butterflymx-buildings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-buildings-api-openapi.yml
- filename: butterflymx-calls-api-openapi.yml
  format: yaml
  label: ButterflyMX Calls API
  slug: butterflymx-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-calls-api-openapi.yml
- filename: butterflymx-devices-api-openapi.yml
  format: yaml
  label: ButterflyMX Devices API
  slug: butterflymx-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-devices-api-openapi.yml
- filename: butterflymx-door-release-requests-api-openapi.yml
  format: yaml
  label: ButterflyMX Door Release Requests API
  slug: butterflymx-door-release-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-door-release-requests-api-openapi.yml
- filename: butterflymx-keychains-api-openapi.yml
  format: yaml
  label: ButterflyMX Keychains API
  slug: butterflymx-keychains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-keychains-api-openapi.yml
- filename: butterflymx-tenant-integrations-api-openapi.yml
  format: yaml
  label: ButterflyMX Tenant Integrations API
  slug: butterflymx-tenant-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-tenant-integrations-api-openapi.yml
- filename: butterflymx-tenants-api-openapi.yml
  format: yaml
  label: ButterflyMX Tenants API
  slug: butterflymx-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-tenants-api-openapi.yml
- filename: butterflymx-units-api-openapi.yml
  format: yaml
  label: ButterflyMX Units API
  slug: butterflymx-units-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-units-api-openapi.yml
- filename: butterflymx-virtual-keys-api-openapi.yml
  format: yaml
  label: ButterflyMX Virtual Keys API
  slug: butterflymx-virtual-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/butterflymx/openapi/butterflymx-virtual-keys-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and/or operated from the United States.
  entity_types:
  - text: If you use the Services on behalf of a company or other entity then
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal, harassing or disruptive use
    text: use the Services for illegal harassing, unethical or disruptive purposes
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
name: ButterflyMX
provenance_date: '2026-11-09'
provider_name: ButterflyMX
provider_slug: butterflymx
slug: butterflymx-eligibility
source_date: '2026-11-09'
source_filename: butterflymx-eligibility.yml
source_heading: Eligibility
source_page: https://butterflymx.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ButterflyMX\naid: butterflymx\nurl: https://butterflymx.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and/or operated from the United States.\nentity_types:\n- type: business\n  text: If you use the Services on behalf of a company or other entity then\nrestricted_uses:\n- summary: Illegal, harassing or disruptive use\n  text: use the Services for illegal harassing, unethical or disruptive purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/butterflymx/eligibility/butterflymx-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from ButterflyMX's own page on 2026-11-09.
synthetic: false
tags:
- Access Control
- physical-access
- smart-intercom
- PropTech
- Property Management
- Multifamily
- Building Automation
- Visitor Management
- IoT
- smart-locks
- OAuth
- Webhook
- Authentication
---
