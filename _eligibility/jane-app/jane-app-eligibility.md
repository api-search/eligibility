---
api_specs:
- filename: jane-app-appointments-api-openapi.yml
  format: yaml
  label: Jane Appointments API
  slug: jane-app-appointments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-appointments-api-openapi.yml
- filename: jane-app-catalog-api-openapi.yml
  format: yaml
  label: Jane Catalog API
  slug: jane-app-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-catalog-api-openapi.yml
- filename: jane-app-company-api-openapi.yml
  format: yaml
  label: Jane Company API
  slug: jane-app-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-company-api-openapi.yml
- filename: jane-app-disciplines-api-openapi.yml
  format: yaml
  label: Jane Disciplines API
  slug: jane-app-disciplines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-disciplines-api-openapi.yml
- filename: jane-app-documentuploads-api-openapi.yml
  format: yaml
  label: Jane Document Uploads API
  slug: jane-app-documentuploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-documentuploads-api-openapi.yml
- filename: jane-app-extensions-api-openapi.yml
  format: yaml
  label: Jane Extensions API
  slug: jane-app-extensions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-extensions-api-openapi.yml
- filename: jane-app-locations-api-openapi.yml
  format: yaml
  label: Jane Locations API
  slug: jane-app-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-locations-api-openapi.yml
- filename: jane-app-medications-api-openapi.yml
  format: yaml
  label: Jane Medications API
  slug: jane-app-medications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-medications-api-openapi.yml
- filename: jane-app-observations-api-openapi.yml
  format: yaml
  label: Jane Observations API
  slug: jane-app-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-observations-api-openapi.yml
- filename: jane-app-patients-api-openapi.yml
  format: yaml
  label: Jane Patients API
  slug: jane-app-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-patients-api-openapi.yml
- filename: jane-app-treatments-api-openapi.yml
  format: yaml
  label: Jane Treatments API
  slug: jane-app-treatments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-treatments-api-openapi.yml
- filename: jane-app-webhooks-api-openapi.yml
  format: yaml
  label: Jane Webhooks API
  slug: jane-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-webhooks-api-openapi.yml
- filename: jane-app-care-plans-api-openapi.yml
  format: yaml
  label: Jane Care Plans API
  slug: jane-app-care-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-care-plans-api-openapi.yml
- filename: jane-app-staff-members-api-openapi.yml
  format: yaml
  label: Jane Staff Members API
  slug: jane-app-staff-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jane-app/openapi/jane-app-staff-members-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    - US
    text: Jane Payroll is currently available to users located in Canada (excluding Quebec) and in select jurisdictions in the United States.
  entity_types:
  - text: If you are entering into these Terms on behalf of a company, organization or another legal entity, you are agreeing to these Terms for that entity
    type: business
  - text: If you cannot enter into this agreement (for reasons such as not being authorized to do so on behalf of an entity, or not being over the age of majority)
    type: individual
  minimum_age:
    text: not being over the age of majority
    value: age of majority
  restricted_uses:
  - summary: No PHI or PII in test accounts
    text: You must not enter, upload, or submit any protected health information, personally identifiable information, or other sensitive data
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
name: Jane
provenance_date: '2026-11-09'
provider_name: Jane
provider_slug: jane-app
slug: jane-app-eligibility
source_date: '2026-11-09'
source_filename: jane-app-eligibility.yml
source_heading: Eligibility
source_page: https://jane.app/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jane\naid: jane-app\nurl: https://jane.app/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  - US\n  excluded: []\n  text: Jane Payroll is currently available to users located in Canada (excluding Quebec) and in select jurisdictions\n    in the United States.\nentity_types:\n- type: business\n  text: If you are entering into these Terms on behalf of a company, organization or another legal entity, you are\n    agreeing to these Terms for that entity\n- type: individual\n  text: If you cannot enter into this agreement (for reasons such as not being authorized to do so on behalf of\n\
  \    an entity, or not being over the age of majority)\nrestricted_uses:\n- summary: No PHI or PII in test accounts\n  text: You must not enter, upload, or submit any protected health information, personally identifiable information,\n    or other sensitive data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: not being over the age of majority\n"
source_yaml_url: https://artifacts.apis.io/jane-app/eligibility/jane-app-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Jane's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Canada
- Practice Management
- Electronic Health Records
- Scheduling
- Clinical Documentation
- Telehealth
- Health and Wellness
- REST API
- OAuth
- Webhook
- Authentication
---
