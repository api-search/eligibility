---
api_specs:
- filename: phenom-applicants-api-openapi.yml
  format: yaml
  label: Phenom Applicants API
  slug: phenom-applicants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-applicants-api-openapi.yml
- filename: phenom-applications-api-openapi.yml
  format: yaml
  label: Phenom Applications API
  slug: phenom-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-applications-api-openapi.yml
- filename: phenom-candidates-api-openapi.yml
  format: yaml
  label: Phenom Candidates API
  slug: phenom-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-candidates-api-openapi.yml
- filename: phenom-jobs-api-openapi.yml
  format: yaml
  label: Phenom Jobs API
  slug: phenom-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-jobs-api-openapi.yml
- filename: phenom-onboarding-api-openapi.yml
  format: yaml
  label: Phenom Onboarding API
  slug: phenom-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-onboarding-api-openapi.yml
- filename: phenom-parsers-api-openapi.yml
  format: yaml
  label: Phenom Parsers API
  slug: phenom-parsers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-parsers-api-openapi.yml
- filename: phenom-prediction-api-openapi.yml
  format: yaml
  label: Phenom Prediction API
  slug: phenom-prediction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-prediction-api-openapi.yml
- filename: phenom-tags-api-openapi.yml
  format: yaml
  label: Phenom Tags API
  slug: phenom-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-tags-api-openapi.yml
- filename: phenom-user-management-api-openapi.yml
  format: yaml
  label: Phenom User Management API
  slug: phenom-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phenom/openapi/phenom-user-management-api-openapi.yml
claim_count: 2
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
  - summary: Unlawful or objectionable material
    text: 'Prohibited uses include sending, knowingly receiving, uploading, downloading, using, or reusing any material which: Is incompatible with applicable laws'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accessing certain parts of the Website requires prior registration. Registering requires You to provide Us with accurate, current, and complete information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Phenom
provenance_date: '2026-11-10'
provider_name: Phenom
provider_slug: phenom
slug: phenom-eligibility
source_date: '2026-11-10'
source_filename: phenom-eligibility.yml
source_heading: Eligibility
source_page: https://www.phenom.com/terms--conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phenom\naid: phenom\nurl: https://www.phenom.com/terms--conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or objectionable material\n  text: 'Prohibited uses include sending, knowingly receiving, uploading, downloading, using, or reusing any material\n    which: Is incompatible with applicable laws'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accessing certain parts of the Website requires prior registration. Registering requires You to provide\n    Us with accurate, current, and\
  \ complete information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/phenom/eligibility/phenom-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Phenom's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Human Resources
- Talent Experience
- Recruiting
- Applicant Tracking
- Candidate Experience
- Onboarding
- SCIM
- Resume Parsing
- Skills
- Artificial Intelligence
---
