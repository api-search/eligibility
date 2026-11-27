---
api_specs:
- filename: microsoft-azure-policy-policyassignments-api-openapi.yml
  format: yaml
  label: Azure Policy Policy Assignments API
  slug: microsoft-azure-policy-policyassignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-policy/openapi/microsoft-azure-policy-policyassignments-api-openapi.yml
- filename: microsoft-azure-policy-policydefinitions-api-openapi.yml
  format: yaml
  label: Azure Policy Policy Definitions API
  slug: microsoft-azure-policy-policydefinitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-policy/openapi/microsoft-azure-policy-policydefinitions-api-openapi.yml
- filename: microsoft-azure-policy-policydefinitionversions-api-openapi.yml
  format: yaml
  label: Azure Policy Policy Definition Versions API
  slug: microsoft-azure-policy-policydefinitionversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-policy/openapi/microsoft-azure-policy-policydefinitionversions-api-openapi.yml
- filename: microsoft-azure-policy-policysetdefinitions-api-openapi.yml
  format: yaml
  label: Azure Policy Policy Set Definitions API
  slug: microsoft-azure-policy-policysetdefinitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-policy/openapi/microsoft-azure-policy-policysetdefinitions-api-openapi.yml
- filename: microsoft-azure-policy-policysetdefinitionversions-api-openapi.yml
  format: yaml
  label: Azure Policy Policy Set Definition Versions API
  slug: microsoft-azure-policy-policysetdefinitionversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-policy/openapi/microsoft-azure-policy-policysetdefinitionversions-api-openapi.yml
- filename: microsoft-azure-policy-providers-api-openapi.yml
  format: yaml
  label: Azure Policy Providers API
  slug: microsoft-azure-policy-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-policy/openapi/microsoft-azure-policy-providers-api-openapi.yml
- filename: microsoft-azure-policy-subscriptions-api-openapi.yml
  format: yaml
  label: Azure Policy Subscriptions API
  slug: microsoft-azure-policy-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microsoft-azure-policy/openapi/microsoft-azure-policy-subscriptions-api-openapi.yml
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
  - summary: AI services restrictions
    text: You may not use web scraping, web harvesting, or web data extraction methods to extract data from the AI services.
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
name: Azure Policy
provenance_date: '2026-11-10'
provider_name: Azure Policy
provider_slug: microsoft-azure-policy
slug: microsoft-azure-policy-eligibility
source_date: '2026-11-10'
source_filename: microsoft-azure-policy-eligibility.yml
source_heading: Eligibility
source_page: https://www.microsoft.com/en-us/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azure Policy\naid: microsoft-azure-policy\nurl: https://www.microsoft.com/en-us/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: AI services restrictions\n  text: You may not use web scraping, web harvesting, or web data extraction methods to extract data from the AI\n    services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/microsoft-azure-policy/eligibility/microsoft-azure-policy-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Azure Policy's own page on 2026-11-10.
synthetic: false
tags:
- Compliance
- Governance
- Policy
- Resource Management
---
