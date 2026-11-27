---
api_specs:
- filename: bcb-group-accounts-api-openapi.yml
  format: yaml
  label: BCB Group Accounts API
  slug: bcb-group-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-accounts-api-openapi.yml
- filename: bcb-group-authentication-api-openapi.yml
  format: yaml
  label: BCB Group Authentication API
  slug: bcb-group-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-authentication-api-openapi.yml
- filename: bcb-group-beneficiaries-api-openapi.yml
  format: yaml
  label: BCB Group Beneficiaries API
  slug: bcb-group-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-beneficiaries-api-openapi.yml
- filename: bcb-group-blinc-api-openapi.yml
  format: yaml
  label: BCB Group BLINC API
  slug: bcb-group-blinc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-blinc-api-openapi.yml
- filename: bcb-group-notifications-api-openapi.yml
  format: yaml
  label: BCB Group Notifications API
  slug: bcb-group-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-notifications-api-openapi.yml
- filename: bcb-group-payments-api-openapi.yml
  format: yaml
  label: BCB Group Payments API
  slug: bcb-group-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-payments-api-openapi.yml
- filename: bcb-group-tools-api-openapi.yml
  format: yaml
  label: BCB Group Tools API
  slug: bcb-group-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-tools-api-openapi.yml
- filename: bcb-group-virtual-accounts-api-openapi.yml
  format: yaml
  label: BCB Group Virtual Accounts API
  slug: bcb-group-virtual-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-virtual-accounts-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a consumer user, please note that we only provide our site for domestic and private use.
    type: individual
  - text: If you are a business user, please note that in particular, we shall not be liable for indirect loss or damage
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use by consumers
    text: You agree not to use our site for any commercial or business purposes
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
name: BCB Group
provenance_date: '2026-11-09'
provider_name: BCB Group
provider_slug: bcb-group
slug: bcb-group-eligibility
source_date: '2026-11-09'
source_filename: bcb-group-eligibility.yml
source_heading: Eligibility
source_page: https://www.bcbgroup.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BCB Group\naid: bcb-group\nurl: https://www.bcbgroup.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a consumer user, please note that we only provide our site for domestic and private use.\n- type: business\n  text: If you are a business user, please note that in particular, we shall not be liable for indirect loss or\n    damage\nrestricted_uses:\n- summary: No commercial use by consumers\n  text: You agree not to use our site for any commercial or business purposes\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bcb-group/eligibility/bcb-group-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from BCB Group's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Banking
- Digital Assets
- Stablecoins
- Financial Services
- Fintech
---
