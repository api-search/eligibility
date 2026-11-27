---
api_specs:
- filename: upwind-access-management-api-openapi.yml
  format: yaml
  label: Upwind Access Management API
  slug: upwind-access-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-access-management-api-openapi.yml
- filename: upwind-api-security-api-openapi.yml
  format: yaml
  label: Upwind API Security API
  slug: upwind-api-security-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-api-security-api-openapi.yml
- filename: upwind-cloud-accounts-api-openapi.yml
  format: yaml
  label: Upwind Cloud Accounts API
  slug: upwind-cloud-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-cloud-accounts-api-openapi.yml
- filename: upwind-configurations-api-openapi.yml
  format: yaml
  label: Upwind Configurations API
  slug: upwind-configurations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-configurations-api-openapi.yml
- filename: upwind-events-api-openapi.yml
  format: yaml
  label: Upwind Events API
  slug: upwind-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-events-api-openapi.yml
- filename: upwind-integrations-api-openapi.yml
  format: yaml
  label: Upwind Integrations API
  slug: upwind-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-integrations-api-openapi.yml
- filename: upwind-inventory-api-openapi.yml
  format: yaml
  label: Upwind Inventory API
  slug: upwind-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-inventory-api-openapi.yml
- filename: upwind-packages-api-openapi.yml
  format: yaml
  label: Upwind Packages API
  slug: upwind-packages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-packages-api-openapi.yml
- filename: upwind-threats-api-openapi.yml
  format: yaml
  label: Upwind Threats API
  slug: upwind-threats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-threats-api-openapi.yml
- filename: upwind-vulnerabilities-api-openapi.yml
  format: yaml
  label: Upwind Vulnerabilities API
  slug: upwind-vulnerabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-vulnerabilities-api-openapi.yml
- filename: upwind-workflows-api-openapi.yml
  format: yaml
  label: Upwind Workflows API
  slug: upwind-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-workflows-api-openapi.yml
- filename: upwind-shift-left-api-openapi.yml
  format: yaml
  label: Upwind Shift Left API
  slug: upwind-shift-left-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upwind/openapi/upwind-shift-left-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into these Terms for an entity, such as the company you work for, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: You represent to Upwind that you are lawfully able to enter into contracts (e.g., you are not a minor).
    value: null
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
name: Upwind
provenance_date: '2026-11-10'
provider_name: Upwind
provider_slug: upwind
slug: upwind-eligibility
source_date: '2026-11-10'
source_filename: upwind-eligibility.yml
source_heading: Eligibility
source_page: https://www.upwind.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Upwind\naid: upwind\nurl: https://www.upwind.io/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into these Terms for an entity, such as the company you work for, you represent that\n    you have authority to bind that entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent to Upwind that you are lawfully able to enter into contracts (e.g., you are not a minor).\n"
source_yaml_url: https://artifacts.apis.io/upwind/eligibility/upwind-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Upwind's own page on 2026-11-10.
synthetic: false
tags:
- Security
- Cloud Security
- CNAPP
- Vulnerability Management
- Container Security
- Kubernetes
- API Security
- Threat Detection
- Data Security
---
