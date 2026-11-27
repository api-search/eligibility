---
api_specs:
- filename: classquill-com-billing-api-openapi.yml
  format: yaml
  label: ClassQuill Billing API
  slug: classquill-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-billing-api-openapi.yml
- filename: classquill-com-blog-api-openapi.yml
  format: yaml
  label: ClassQuill Blog API
  slug: classquill-com-blog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-blog-api-openapi.yml
- filename: classquill-com-bookings-api-openapi.yml
  format: yaml
  label: ClassQuill Bookings API
  slug: classquill-com-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-bookings-api-openapi.yml
- filename: classquill-com-coursework-api-openapi.yml
  format: yaml
  label: ClassQuill Coursework API
  slug: classquill-com-coursework-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-coursework-api-openapi.yml
- filename: classquill-com-curriculum-api-openapi.yml
  format: yaml
  label: ClassQuill Curriculum API
  slug: classquill-com-curriculum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-curriculum-api-openapi.yml
- filename: classquill-com-general-api-openapi.yml
  format: yaml
  label: ClassQuill General API
  slug: classquill-com-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-general-api-openapi.yml
- filename: classquill-com-operations-api-openapi.yml
  format: yaml
  label: ClassQuill Operations API
  slug: classquill-com-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-operations-api-openapi.yml
- filename: classquill-com-pricing-api-openapi.yml
  format: yaml
  label: ClassQuill Pricing API
  slug: classquill-com-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-pricing-api-openapi.yml
- filename: classquill-com-reports-api-openapi.yml
  format: yaml
  label: ClassQuill Reports API
  slug: classquill-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-reports-api-openapi.yml
- filename: classquill-com-sessions-api-openapi.yml
  format: yaml
  label: ClassQuill Sessions API
  slug: classquill-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-sessions-api-openapi.yml
- filename: classquill-com-students-parents-api-openapi.yml
  format: yaml
  label: ClassQuill Students & Parents API
  slug: classquill-com-students-parents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-students-parents-api-openapi.yml
- filename: classquill-com-tutors-api-openapi.yml
  format: yaml
  label: ClassQuill Tutors API
  slug: classquill-com-tutors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classquill-com/openapi/classquill-com-tutors-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years or older to create an account on behalf of a business or organisation.
    type: business
  minimum_age:
    text: You must be 18 years or older to create an account on behalf of a business or organisation.
    value: '18'
  restricted_uses:
  - summary: Unlawful or unauthorised use
    text: You may not use the Service for any illegal or unauthorised purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your name, a valid email address, and any other information requested in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClassQuill
provenance_date: '2026-11-09'
provider_name: ClassQuill
provider_slug: classquill-com
slug: classquill-com-eligibility
source_date: '2026-11-09'
source_filename: classquill-com-eligibility.yml
source_heading: Eligibility
source_page: https://classquill.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClassQuill\naid: classquill-com\nurl: https://classquill.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You must be 18 years or older to create an account on behalf of a business or organisation.\nrestricted_uses:\n- summary: Unlawful or unauthorised use\n  text: You may not use the Service for any illegal or unauthorised purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your name, a valid email address, and any other information requested in order to complete\n\
  \    the signup process.\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to create an account on behalf of a business or organisation.\n"
source_yaml_url: https://artifacts.apis.io/classquill-com/eligibility/classquill-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from ClassQuill's own page on 2026-11-09.
synthetic: false
tags:
- Tutoring
- Scheduling
- Invoicing
- Payroll
- Learning Platform
- Education
---
