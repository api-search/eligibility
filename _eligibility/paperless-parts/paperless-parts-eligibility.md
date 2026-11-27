---
api_specs:
- filename: paperless-parts-contacts-api-openapi.yml
  format: yaml
  label: Paperless Parts Contacts API
  slug: paperless-parts-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-contacts-api-openapi.yml
- filename: paperless-parts-custom-tables-api-openapi.yml
  format: yaml
  label: Paperless Parts Custom Tables API
  slug: paperless-parts-custom-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-custom-tables-api-openapi.yml
- filename: paperless-parts-customers-api-openapi.yml
  format: yaml
  label: Paperless Parts Customers API
  slug: paperless-parts-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-customers-api-openapi.yml
- filename: paperless-parts-events-api-openapi.yml
  format: yaml
  label: Paperless Parts Events API
  slug: paperless-parts-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-events-api-openapi.yml
- filename: paperless-parts-integration-actions-api-openapi.yml
  format: yaml
  label: Paperless Parts Integration Actions API
  slug: paperless-parts-integration-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-integration-actions-api-openapi.yml
- filename: paperless-parts-jobs-api-openapi.yml
  format: yaml
  label: Paperless Parts Jobs API
  slug: paperless-parts-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-jobs-api-openapi.yml
- filename: paperless-parts-orders-api-openapi.yml
  format: yaml
  label: Paperless Parts Orders API
  slug: paperless-parts-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-orders-api-openapi.yml
- filename: paperless-parts-parts-api-openapi.yml
  format: yaml
  label: Paperless Parts API
  slug: paperless-parts-parts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-parts-api-openapi.yml
- filename: paperless-parts-processes-api-openapi.yml
  format: yaml
  label: Paperless Parts Processes API
  slug: paperless-parts-processes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-processes-api-openapi.yml
- filename: paperless-parts-purchased-components-api-openapi.yml
  format: yaml
  label: Paperless Parts Purchased Components API
  slug: paperless-parts-purchased-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-purchased-components-api-openapi.yml
- filename: paperless-parts-quote-items-api-openapi.yml
  format: yaml
  label: Paperless Parts Quote Items API
  slug: paperless-parts-quote-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-quote-items-api-openapi.yml
- filename: paperless-parts-quotes-api-openapi.yml
  format: yaml
  label: Paperless Parts Quotes API
  slug: paperless-parts-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paperless-parts/openapi/paperless-parts-quotes-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are an Entity, by using any of our Offerings and/or accepting these General Terms, the individual doing so thereby represents and warrants to Paperless Parts that s/he is Your employee
    type: business
  minimum_age:
    text: The Services are not intended for and should not be used by anyone under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Inherently dangerous applications
    text: Use the Offerings in connection with any inherently dangerous application, including any application that could result in death, personal injury, catastrophic damage or mass destruction
  - summary: Sensitive personal information
    text: The data storage functionality associated with Offerings is NOT suitable for the storage of Social Security numbers, credit or debit card numbers, financial account numbers
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
name: Paperless Parts
provenance_date: '2026-11-10'
provider_name: Paperless Parts
provider_slug: paperless-parts
slug: paperless-parts-eligibility
source_date: '2026-11-10'
source_filename: paperless-parts-eligibility.yml
source_heading: Eligibility
source_page: https://help.paperlessparts.com/s/article/general-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paperless Parts\naid: paperless-parts\nurl: https://help.paperlessparts.com/s/article/general-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are an Entity, by using any of our Offerings and/or accepting these General Terms, the individual\n    doing so thereby represents and warrants to Paperless Parts that s/he is Your employee\nrestricted_uses:\n- summary: Inherently dangerous applications\n  text: Use the Offerings in connection with any inherently dangerous application, including any application that\n\
  \    could result in death, personal injury, catastrophic damage or mass destruction\n- summary: Sensitive personal information\n  text: The data storage functionality associated with Offerings is NOT suitable for the storage of Social Security\n    numbers, credit or debit card numbers, financial account numbers\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for and should not be used by anyone under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/paperless-parts/eligibility/paperless-parts-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Paperless Parts's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manufacturing
- Quoting
- CNC Machining
- Sheet Metal
- ERP
- CRM
- Job Shops
- Aerospace and Defense
- Pricing
- Estimating
- Industrial
---
