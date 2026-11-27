---
api_specs:
- filename: halaxy-appointment-api-openapi.yml
  format: yaml
  label: Halaxy Appointment API
  slug: halaxy-appointment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-appointment-api-openapi.yml
- filename: halaxy-chargeitemdefinition-api-openapi.yml
  format: yaml
  label: Halaxy Charge Item Definition API
  slug: halaxy-chargeitemdefinition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-chargeitemdefinition-api-openapi.yml
- filename: halaxy-coverage-api-openapi.yml
  format: yaml
  label: Halaxy Coverage API
  slug: halaxy-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-coverage-api-openapi.yml
- filename: halaxy-invoice-api-openapi.yml
  format: yaml
  label: Halaxy Invoice API
  slug: halaxy-invoice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-invoice-api-openapi.yml
- filename: halaxy-invoiceline-api-openapi.yml
  format: yaml
  label: Halaxy Invoice Line API
  slug: halaxy-invoiceline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-invoiceline-api-openapi.yml
- filename: halaxy-organization-api-openapi.yml
  format: yaml
  label: Halaxy Organization API
  slug: halaxy-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-organization-api-openapi.yml
- filename: halaxy-patient-api-openapi.yml
  format: yaml
  label: Halaxy Patient API
  slug: halaxy-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-patient-api-openapi.yml
- filename: halaxy-paymenttransaction-api-openapi.yml
  format: yaml
  label: Halaxy Payment Transaction API
  slug: halaxy-paymenttransaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-paymenttransaction-api-openapi.yml
- filename: halaxy-practitioner-api-openapi.yml
  format: yaml
  label: Halaxy Practitioner API
  slug: halaxy-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-practitioner-api-openapi.yml
- filename: halaxy-referral-api-openapi.yml
  format: yaml
  label: Halaxy Referral API
  slug: halaxy-referral-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-referral-api-openapi.yml
- filename: halaxy-referraldefinition-api-openapi.yml
  format: yaml
  label: Halaxy Referral Definition API
  slug: halaxy-referraldefinition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-referraldefinition-api-openapi.yml
- filename: halaxy-schedule-api-openapi.yml
  format: yaml
  label: Halaxy Schedule API
  slug: halaxy-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-schedule-api-openapi.yml
- filename: halaxy-slot-api-openapi.yml
  format: yaml
  label: Halaxy Slot API
  slug: halaxy-slot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-slot-api-openapi.yml
- filename: halaxy-capability-statement-api-openapi.yml
  format: yaml
  label: Halaxy Capability Statement API
  slug: halaxy-capability-statement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-capability-statement-api-openapi.yml
- filename: halaxy-document-reference-api-openapi.yml
  format: yaml
  label: Halaxy Document Reference API
  slug: halaxy-document-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-document-reference-api-openapi.yml
- filename: halaxy-healthcare-service-api-openapi.yml
  format: yaml
  label: Halaxy Healthcare Service API
  slug: halaxy-healthcare-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-healthcare-service-api-openapi.yml
- filename: halaxy-practitioner-role-api-openapi.yml
  format: yaml
  label: Halaxy Practitioner Role API
  slug: halaxy-practitioner-role-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-practitioner-role-api-openapi.yml
- filename: halaxy-search-parameter-api-openapi.yml
  format: yaml
  label: Halaxy Search Parameter API
  slug: halaxy-search-parameter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halaxy/openapi/halaxy-search-parameter-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To create an account, you must be: at least 18 years of age; possess the legal right and ability to enter into a legally binding agreement with us'
    type: individual
  minimum_age:
    text: at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Business use only
    text: The website can only be used for your business and not personal use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: properly registered or qualified in the profession you state when you sign up
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Halaxy
provenance_date: '2026-11-09'
provider_name: Halaxy
provider_slug: halaxy
slug: halaxy-eligibility
source_date: '2026-11-09'
source_filename: halaxy-eligibility.yml
source_heading: Eligibility
source_page: https://www.halaxy.com/terms/practitioner/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halaxy\naid: halaxy\nurl: https://www.halaxy.com/terms/practitioner/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To create an account, you must be: at least 18 years of age; possess the legal right and ability to enter\n    into a legally binding agreement with us'\nrestricted_uses:\n- summary: Business use only\n  text: The website can only be used for your business and not personal use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: properly registered or qualified in the profession you state when\
  \ you sign up\nminimum_age:\n  value: '18'\n  text: at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/halaxy/eligibility/halaxy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Halaxy's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Practice Management
- FHIR
- Telehealth
- Appointments
- Billing
- Patients
---
