---
api_specs:
- filename: drip-accounts-api-openapi.yml
  format: yaml
  label: Drip Accounts API
  slug: drip-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-accounts-api-openapi.yml
- filename: drip-broadcasts-api-openapi.yml
  format: yaml
  label: Drip Broadcasts API
  slug: drip-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-broadcasts-api-openapi.yml
- filename: drip-campaigns-api-openapi.yml
  format: yaml
  label: Drip Campaigns API
  slug: drip-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-campaigns-api-openapi.yml
- filename: drip-conversions-api-openapi.yml
  format: yaml
  label: Drip Conversions API
  slug: drip-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-conversions-api-openapi.yml
- filename: drip-custom-fields-api-openapi.yml
  format: yaml
  label: Drip Custom Fields API
  slug: drip-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-custom-fields-api-openapi.yml
- filename: drip-events-api-openapi.yml
  format: yaml
  label: Drip Events API
  slug: drip-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-events-api-openapi.yml
- filename: drip-forms-api-openapi.yml
  format: yaml
  label: Drip Forms API
  slug: drip-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-forms-api-openapi.yml
- filename: drip-orders-api-openapi.yml
  format: yaml
  label: Drip Orders API
  slug: drip-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-orders-api-openapi.yml
- filename: drip-shopper-activity-api-openapi.yml
  format: yaml
  label: Drip Shopper Activity API
  slug: drip-shopper-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-shopper-activity-api-openapi.yml
- filename: drip-subscribers-api-openapi.yml
  format: yaml
  label: Drip Subscribers API
  slug: drip-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drip/openapi/drip-subscribers-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: (v) be based in any country that is subject to a U.S. government embargo, or that has been designated by the U.S. government as a 'terrorist-supporting' country.
  minimum_age:
    text: Any use or access to Drip by anyone under eighteen (18) years of age is strictly prohibited and in violation of this Agreement.
    value: '18'
  restricted_uses:
  - summary: Children under 13 in customer lists
    text: you will not, either directly or indirectly, direct us to send communications to any person under the age of thirteen (13) years of age
  - summary: Cannabis/CBD via Drip SMS
    text: you cannot use Drip SMS service to promote such business.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Drip may refuse service, close accounts of any users, and change eligibility requirements at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Drip
provenance_date: '2026-11-09'
provider_name: Drip
provider_slug: drip
slug: drip-eligibility
source_date: '2026-11-09'
source_filename: drip-eligibility.yml
source_heading: Eligibility
source_page: https://www.drip.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Drip\naid: drip\nurl: https://www.drip.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: (v) be based in any country that is subject to a U.S. government embargo, or that has been designated by\n    the U.S. government as a 'terrorist-supporting' country.\nentity_types: []\nrestricted_uses:\n- summary: Children under 13 in customer lists\n  text: you will not, either directly or indirectly, direct us to send communications to any person under the age\n    of thirteen (13) years of age\n- summary: Cannabis/CBD via Drip SMS\n  text: you cannot use Drip SMS service to promote\
  \ such business.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Drip may refuse service, close accounts of any users, and change eligibility requirements at any time.\nminimum_age:\n  value: '18'\n  text: Any use or access to Drip by anyone under eighteen (18) years of age is strictly prohibited and in violation\n    of this Agreement.\n"
source_yaml_url: https://artifacts.apis.io/drip/eligibility/drip-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Drip's own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Marketing Automation
- E-Commerce
- Customer Engagement
- Campaigns
- Workflows
---
