---
api_specs:
- filename: revenuebase-account-api-openapi.yml
  format: yaml
  label: RevenueBase Account API
  slug: revenuebase-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-account-api-openapi.yml
- filename: revenuebase-email-api-openapi.yml
  format: yaml
  label: RevenueBase Email API
  slug: revenuebase-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-email-api-openapi.yml
- filename: revenuebase-jobs-api-openapi.yml
  format: yaml
  label: RevenueBase Jobs API
  slug: revenuebase-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-jobs-api-openapi.yml
- filename: revenuebase-organization-api-openapi.yml
  format: yaml
  label: RevenueBase Organization API
  slug: revenuebase-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-organization-api-openapi.yml
- filename: revenuebase-health-api-openapi.yml
  format: yaml
  label: RevenueBase Health API
  slug: revenuebase-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-health-api-openapi.yml
- filename: revenuebase-contact-api-openapi.yml
  format: yaml
  label: RevenueBase Contact API
  slug: revenuebase-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revenuebase/openapi/revenuebase-contact-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - SD
    - SY
    - KP
    served: []
    text: Individuals or entities owned or controlled, registered in, or related to Cuba, Iran, Sudan, Syria, or North Korea are not permitted to use Licensed Materials without prior written permission from RevenueBase, Inc.
  entity_types:
  - text: “Customer” means the legal entity identified under the applicable Order Form.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export controls and sanctions
    text: Individuals or entities owned or controlled, registered in, or related to Cuba, Iran, Sudan, Syria, or North Korea are not permitted to use Licensed Materials without prior written permission from RevenueBase, Inc.
  - summary: Do Not Call and Do Not Track cross-check
    text: RevenueBase, Inc. will cross reference against the United States’ “Do Not Call Registry” and “Do Not Track” lists to confirm it is permissible to share such information with Customer prior to doing so.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- SD
- SY
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RevenueBase
provenance_date: '2026-11-10'
provider_name: RevenueBase
provider_slug: revenuebase
slug: revenuebase-eligibility
source_date: '2026-11-10'
source_filename: revenuebase-eligibility.yml
source_heading: Eligibility
source_page: https://revenuebase.ai/stc-01-14-2024
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RevenueBase\naid: revenuebase\nurl: https://revenuebase.ai/stc-01-14-2024\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - SD\n  - SY\n  - KP\n  text: Individuals or entities owned or controlled, registered in, or related to Cuba, Iran, Sudan, Syria, or North\n    Korea are not permitted to use Licensed Materials without prior written permission from RevenueBase, Inc.\nentity_types:\n- type: business\n  text: “Customer” means the legal entity identified under the applicable Order Form.\nrestricted_uses:\n- summary: Export controls and sanctions\n  text: Individuals or entities\
  \ owned or controlled, registered in, or related to Cuba, Iran, Sudan, Syria, or North\n    Korea are not permitted to use Licensed Materials without prior written permission from RevenueBase, Inc.\n- summary: Do Not Call and Do Not Track cross-check\n  text: RevenueBase, Inc. will cross reference against the United States’ “Do Not Call Registry” and “Do Not Track”\n    lists to confirm it is permissible to share such information with Customer prior to doing so.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/revenuebase/eligibility/revenuebase-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from RevenueBase's own page on 2026-11-10.
synthetic: false
tags:
- Company
- B2B Data
- Data Enrichment
- Email Verification
- Contact Data
- Company Data
- Lead Intelligence
- Sales Intelligence
- A2A
---
