---
api_specs:
- filename: billingengine-customers-api-openapi.yml
  format: yaml
  label: BillingEngine Customers API
  slug: billingengine-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billingengine/openapi/billingengine-customers-api-openapi.yml
- filename: billingengine-invoices-api-openapi.yml
  format: yaml
  label: BillingEngine Invoices API
  slug: billingengine-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billingengine/openapi/billingengine-invoices-api-openapi.yml
- filename: billingengine-payments-api-openapi.yml
  format: yaml
  label: BillingEngine Payments API
  slug: billingengine-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billingengine/openapi/billingengine-payments-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: BillingEngine richtet sich ausschließlich an Unternehmer (§ 14 BGB).
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Mit der Registrierung bestätigen Sie, BillingEngine für Ihre gewerbliche oder selbstständige Tätigkeit zu nutzen.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BillingEngine
provenance_date: '2026-11-09'
provider_name: BillingEngine
provider_slug: billingengine
slug: billingengine-eligibility
source_date: '2026-11-09'
source_filename: billingengine-eligibility.yml
source_heading: Eligibility
source_page: https://www.billingengine.com/de/terms_of_service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BillingEngine\naid: billingengine\nurl: https://www.billingengine.com/de/terms_of_service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: BillingEngine richtet sich ausschließlich an Unternehmer (§ 14 BGB).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Mit der Registrierung bestätigen Sie, BillingEngine für Ihre gewerbliche oder selbstständige Tätigkeit zu\n    nutzen.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/billingengine/eligibility/billingengine-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from BillingEngine's own page on 2026-11-09.
synthetic: false
tags:
- Invoicing
- Fintech
- Germany
- Small Business
---
