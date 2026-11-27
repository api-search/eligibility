---
api_specs:
- filename: zenadmin-catalog-api-openapi.yml
  format: yaml
  label: ZenAdmin Catalog API
  slug: zenadmin-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenadmin/openapi/zenadmin-catalog-api-openapi.yml
- filename: zenadmin-context-api-openapi.yml
  format: yaml
  label: ZenAdmin Context API
  slug: zenadmin-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenadmin/openapi/zenadmin-context-api-openapi.yml
- filename: zenadmin-devices-api-openapi.yml
  format: yaml
  label: ZenAdmin Devices API
  slug: zenadmin-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenadmin/openapi/zenadmin-devices-api-openapi.yml
- filename: zenadmin-employees-api-openapi.yml
  format: yaml
  label: ZenAdmin Employees API
  slug: zenadmin-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenadmin/openapi/zenadmin-employees-api-openapi.yml
- filename: zenadmin-orders-api-openapi.yml
  format: yaml
  label: ZenAdmin Orders API
  slug: zenadmin-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenadmin/openapi/zenadmin-orders-api-openapi.yml
- filename: zenadmin-webhooks-api-openapi.yml
  format: yaml
  label: ZenAdmin Webhooks API
  slug: zenadmin-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zenadmin/openapi/zenadmin-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you sign up for ZenAdmin on behalf of a company or other entity, you represent and warrant that you have the authority to accept this Agreement on behalf of said company or other entity.
    type: business
  minimum_age:
    text: Be at least eighteen (18) years old, of sound mind, and otherwise legally competent to enter into contracts.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You represent that You are not named on any government list of persons or entities prohibited from receiving export and that You shall not access or use the Service in violation of any export embargo, prohibition, or restriction.
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
name: ZenAdmin
provenance_date: '2026-11-10'
provider_name: ZenAdmin
provider_slug: zenadmin
slug: zenadmin-eligibility
source_date: '2026-11-10'
source_filename: zenadmin-eligibility.yml
source_heading: Eligibility
source_page: https://www.zenadmin.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZenAdmin\naid: zenadmin\nurl: https://www.zenadmin.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you sign up for ZenAdmin on behalf of a company or other entity, you represent and warrant that you have\n    the authority to accept this Agreement on behalf of said company or other entity.\nrestricted_uses:\n- summary: Export restrictions\n  text: You represent that You are not named on any government list of persons or entities prohibited from receiving\n    export and that You shall not access or use the Service\
  \ in violation of any export embargo, prohibition, or\n    restriction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least eighteen (18) years old, of sound mind, and otherwise legally competent to enter into contracts.\n"
source_yaml_url: https://artifacts.apis.io/zenadmin/eligibility/zenadmin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ZenAdmin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- IT Management
- Device Management
- Mobile Device Management
- IT Asset Management
- SaaS Management
- IT Procurement
- Employee Lifecycle
- Webhook
---
