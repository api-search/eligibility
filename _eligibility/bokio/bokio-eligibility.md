---
api_specs:
- filename: bokio-authorization-api-openapi.yml
  format: yaml
  label: Bokio Authorization API
  slug: bokio-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-authorization-api-openapi.yml
- filename: bokio-bank-payments-api-openapi.yml
  format: yaml
  label: Bokio Bank Payments API
  slug: bokio-bank-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-bank-payments-api-openapi.yml
- filename: bokio-chart-of-accounts-api-openapi.yml
  format: yaml
  label: Bokio Chart Of Accounts API
  slug: bokio-chart-of-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-chart-of-accounts-api-openapi.yml
- filename: bokio-company-information-api-openapi.yml
  format: yaml
  label: Bokio Company Information API
  slug: bokio-company-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-company-information-api-openapi.yml
- filename: bokio-connections-api-openapi.yml
  format: yaml
  label: Bokio Connections API
  slug: bokio-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-connections-api-openapi.yml
- filename: bokio-credit-notes-api-openapi.yml
  format: yaml
  label: Bokio Credit Notes API
  slug: bokio-credit-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-credit-notes-api-openapi.yml
- filename: bokio-customers-api-openapi.yml
  format: yaml
  label: Bokio Customers API
  slug: bokio-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-customers-api-openapi.yml
- filename: bokio-fiscal-years-api-openapi.yml
  format: yaml
  label: Bokio Fiscal Years API
  slug: bokio-fiscal-years-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-fiscal-years-api-openapi.yml
- filename: bokio-invoices-api-openapi.yml
  format: yaml
  label: Bokio Invoices API
  slug: bokio-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-invoices-api-openapi.yml
- filename: bokio-items-api-openapi.yml
  format: yaml
  label: Bokio Items API
  slug: bokio-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-items-api-openapi.yml
- filename: bokio-journal-entries-api-openapi.yml
  format: yaml
  label: Bokio Journal Entries API
  slug: bokio-journal-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-journal-entries-api-openapi.yml
- filename: bokio-sie-files-api-openapi.yml
  format: yaml
  label: Bokio Sie Files API
  slug: bokio-sie-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-sie-files-api-openapi.yml
- filename: bokio-supplier-invoices-api-openapi.yml
  format: yaml
  label: Bokio Supplier Invoices API
  slug: bokio-supplier-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-supplier-invoices-api-openapi.yml
- filename: bokio-suppliers-api-openapi.yml
  format: yaml
  label: Bokio Suppliers API
  slug: bokio-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-suppliers-api-openapi.yml
- filename: bokio-tag-groups-api-openapi.yml
  format: yaml
  label: Bokio Tag Groups API
  slug: bokio-tag-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-tag-groups-api-openapi.yml
- filename: bokio-uploads-api-openapi.yml
  format: yaml
  label: Bokio Uploads API
  slug: bokio-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bokio/openapi/bokio-uploads-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: by end-users of the Application (the “ End User ”) for linking third-party applications with the Application
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful activities
    text: to disrupt, interfere with, or attempt to gain unauthorised access to any services, servers, devices or networks connected to or accessible through the API
  - summary: Spamming
    text: to access, collect, download, or use data or content for spamming or unsolicited communications, including any activity that would violate any applicable law.
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
name: Bokio
provenance_date: '2026-11-09'
provider_name: Bokio
provider_slug: bokio
slug: bokio-eligibility
source_date: '2026-11-09'
source_filename: bokio-eligibility.yml
source_heading: Eligibility
source_page: https://docs.bokio.se/page/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bokio\naid: bokio\nurl: https://docs.bokio.se/page/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: by end-users of the Application (the “ End User ”) for linking third-party applications with the Application\nrestricted_uses:\n- summary: Illegal or harmful activities\n  text: to disrupt, interfere with, or attempt to gain unauthorised access to any services, servers, devices or\n    networks connected to or accessible through the API\n- summary: Spamming\n  text: to access, collect, download, or use data or content for spamming\
  \ or unsolicited communications, including\n    any activity that would violate any applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bokio/eligibility/bokio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Bokio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Bookkeeping
- Invoicing
- Payments
- Sweden
- Small Business
- OAuth
- Authentication
---
