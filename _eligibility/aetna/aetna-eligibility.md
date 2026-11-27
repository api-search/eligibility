---
api_specs:
- filename: aetna-endpoint-api-openapi.yml
  format: yaml
  label: Aetna Endpoint API
  slug: aetna-endpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-endpoint-api-openapi.yml
- filename: aetna-location-api-openapi.yml
  format: yaml
  label: Aetna Location API
  slug: aetna-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-location-api-openapi.yml
- filename: aetna-organization-api-openapi.yml
  format: yaml
  label: Aetna Organization API
  slug: aetna-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-organization-api-openapi.yml
- filename: aetna-organizationaffiliation-api-openapi.yml
  format: yaml
  label: Aetna Organization Affiliation API
  slug: aetna-organizationaffiliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-organizationaffiliation-api-openapi.yml
- filename: aetna-practitioner-api-openapi.yml
  format: yaml
  label: Aetna Practitioner API
  slug: aetna-practitioner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-practitioner-api-openapi.yml
- filename: aetna-providerdirectorydata-api-openapi.yml
  format: yaml
  label: Aetna Providerdirectorydata API
  slug: aetna-providerdirectorydata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-providerdirectorydata-api-openapi.yml
- filename: aetna-patient-access-api-openapi.yml
  format: yaml
  label: Aetna Patient Access API
  slug: aetna-patient-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-patient-access-api-openapi.yml
- filename: aetna-provider-directory-api-openapi.yml
  format: yaml
  label: Aetna Provider Directory API
  slug: aetna-provider-directory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-provider-directory-api-openapi.yml
- filename: aetna-healthcare-service-api-openapi.yml
  format: yaml
  label: Aetna Healthcare Service API
  slug: aetna-healthcare-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-healthcare-service-api-openapi.yml
- filename: aetna-insurance-plan-api-openapi.yml
  format: yaml
  label: Aetna Insurance Plan API
  slug: aetna-insurance-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-insurance-plan-api-openapi.yml
- filename: aetna-practitioner-role-api-openapi.yml
  format: yaml
  label: Aetna Practitioner Role API
  slug: aetna-practitioner-role-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aetna/openapi/aetna-practitioner-role-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We control the Service from our corporate offices within the United States of America, and the Service is not intended to subject Aetna to any non-U.S. jurisdiction or law.
  minimum_age:
    text: By using the Service, you affirm that you are of legal age to enter into this Agreement
    value: null
  restricted_uses:
  - summary: No eligibility, underwriting or similar decisions
    text: use the Service or data obtained from the Service to make eligibility, underwriting, marketing, employment, lending, or other decisions not authorized by applicable law
  - summary: Lawful use only
    text: You agree to use the Service only for lawful purposes.
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
name: Aetna
provenance_date: '2026-11-09'
provider_name: Aetna
provider_slug: aetna
slug: aetna-eligibility
source_date: '2026-11-09'
source_filename: aetna-eligibility.yml
source_heading: Eligibility
source_page: https://developerportal.aetna.com/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aetna\naid: aetna\nurl: https://developerportal.aetna.com/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We control the Service from our corporate offices within the United States of America, and the Service is\n    not intended to subject Aetna to any non-U.S. jurisdiction or law.\nentity_types: []\nrestricted_uses:\n- summary: No eligibility, underwriting or similar decisions\n  text: use the Service or data obtained from the Service to make eligibility, underwriting, marketing, employment,\n    lending, or other decisions not authorized by applicable law\n- summary:\
  \ Lawful use only\n  text: You agree to use the Service only for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: By using the Service, you affirm that you are of legal age to enter into this Agreement\n"
source_yaml_url: https://artifacts.apis.io/aetna/eligibility/aetna-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Aetna's own page on 2026-11-09.
synthetic: false
tags:
- Health Insurance
- Healthcare
- FHIR
- Patient Access
- Provider Directory
- Drug Formulary
- Prior Authorization
- CMS Interoperability
- SMART on FHIR
- CARIN Blue Button
- Da Vinci
- Payers
- Fortune 100
- CVS Health
---
