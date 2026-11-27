---
api_specs:
- filename: alectra-utilities-applicationinformation-api-openapi.yml
  format: yaml
  label: Alectra Utilities Application Information API
  slug: alectra-utilities-applicationinformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alectra-utilities/openapi/alectra-utilities-applicationinformation-api-openapi.yml
- filename: alectra-utilities-authorization-api-openapi.yml
  format: yaml
  label: Alectra Utilities Authorization API
  slug: alectra-utilities-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alectra-utilities/openapi/alectra-utilities-authorization-api-openapi.yml
- filename: alectra-utilities-batch-api-openapi.yml
  format: yaml
  label: Alectra Utilities Batch API
  slug: alectra-utilities-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alectra-utilities/openapi/alectra-utilities-batch-api-openapi.yml
- filename: alectra-utilities-usagepoint-api-openapi.yml
  format: yaml
  label: Alectra Utilities Usage Point API
  slug: alectra-utilities-usagepoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alectra-utilities/openapi/alectra-utilities-usagepoint-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: federal laws of Canada applicable therein
  entity_types:
  - text: When you register with Alectra to participate in the Green Button Connect My Data Service as a Third Party Provider, you agree to accept and be bound by all of these terms and conditions
    type: other
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: After successful completion of the registration and on-boarding process, you’ll be approved as a third-party provider to Alectra Utilities and/or Guelph Hydro customer data as authorized.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alectra Utilities
provenance_date: '2026-11-09'
provider_name: Alectra Utilities
provider_slug: alectra-utilities
slug: alectra-utilities-eligibility
source_date: '2026-11-09'
source_filename: alectra-utilities-eligibility.yml
source_heading: Eligibility
source_page: https://alectrautilities.com/green-button-connect-my-data-terms-and-conditions-access-and-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alectra Utilities\naid: alectra-utilities\nurl: https://alectrautilities.com/green-button-connect-my-data-terms-and-conditions-access-and-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: federal laws of Canada applicable therein\nentity_types:\n- type: other\n  text: When you register with Alectra to participate in the Green Button Connect My Data Service as a Third Party\n    Provider, you agree to accept and be bound by all of these terms and conditions\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: After successful completion\
  \ of the registration and on-boarding process, you’ll be approved as a third-party\n    provider to Alectra Utilities and/or Guelph Hydro customer data as authorized.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alectra-utilities/eligibility/alectra-utilities-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
summary_line: 3 quoted statements, read from Alectra Utilities's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Canada
- Utilities
- Electricity
- Ontario
- Green Button
- Smart Metering
- Energy Data
- Grid
- Municipal Utility
- ESPI
---
