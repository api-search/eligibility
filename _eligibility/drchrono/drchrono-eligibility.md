---
api_specs:
- filename: drchrono-administrative-api-openapi.yml
  format: yaml
  label: drchrono Administrative API
  slug: drchrono-administrative-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-administrative-api-openapi.yml
- filename: drchrono-audit-api-openapi.yml
  format: yaml
  label: drchrono Audit API
  slug: drchrono-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-audit-api-openapi.yml
- filename: drchrono-availability-api-openapi.yml
  format: yaml
  label: drchrono Availability API
  slug: drchrono-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-availability-api-openapi.yml
- filename: drchrono-billing-api-openapi.yml
  format: yaml
  label: drchrono Billing API
  slug: drchrono-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-billing-api-openapi.yml
- filename: drchrono-clinical-api-openapi.yml
  format: yaml
  label: drchrono Clinical API
  slug: drchrono-clinical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-clinical-api-openapi.yml
- filename: drchrono-practice-management-api-openapi.yml
  format: yaml
  label: drchrono Practice Management API
  slug: drchrono-practice-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/drchrono/openapi/drchrono-practice-management-api-openapi.yml
claim_count: 3
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
  - summary: Illegal or harmful content and PCI-regulated data
    text: (d) knowingly input or post through or to the Services any content that is illegal, threatening, harmful, lewd, offensive, or defamatory
  - source: https://www.drchrono.com/api-development-terms-conditions/
    summary: Illegal or harmful content
    text: knowingly input or post through or to the Services any content that is illegal, threatening, harmful, lewd, offensive, or defamatory
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Developer will be required to register by establishing a developer account and provide certain information such as contact information
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: drchrono
provenance_date: '2026-11-09'
provider_name: drchrono
provider_slug: drchrono
slug: drchrono-eligibility
source_date: '2026-11-09'
source_filename: drchrono-eligibility.yml
source_heading: Eligibility
source_page: https://app.drchrono.com/api-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: drchrono\naid: drchrono\nurl: https://app.drchrono.com/api-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://app.drchrono.com/api-terms/\n  - https://www.drchrono.com/api-development-terms-conditions/\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful content and PCI-regulated data\n  text: (d) knowingly input or post through or to the Services any content that is illegal, threatening, harmful,\n    lewd, offensive, or defamatory\n- summary: Illegal or harmful content\n  text: knowingly input or post through or to the Services any\
  \ content that is illegal, threatening, harmful, lewd,\n    offensive, or defamatory\n  source: https://www.drchrono.com/api-development-terms-conditions/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Developer will be required to register by establishing a developer account and provide certain information\n    such as contact information\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/drchrono/eligibility/drchrono-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from drchrono's own page on 2026-11-09.
synthetic: false
tags:
- Electronic Health Records
- Healthcare
- Medical Records
- Practice Management
- HIPAA
- Appointments
- Billing
- Prescriptions
- Lab Integration
- FHIR
- SMART on FHIR
- USCDI
- Interoperability
- Webhook
- Authentication
- ONC Certified
- Telehealth
- Revenue Cycle Management
---
