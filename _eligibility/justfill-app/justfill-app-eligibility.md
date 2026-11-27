---
api_specs:
- filename: justfill-app-openapi-generated.yml
  format: yaml
  label: justfill-app API
  slug: justfill-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/justfill-app/openapi/_ae-authored/justfill-app-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to create a JustFill account and use the Service.
    type: individual
  - text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create a JustFill account and use the Service.
    value: '18'
  restricted_uses:
  - summary: No PHI or regulated health data
    text: This Section 4E sets forth an absolute prohibition on the upload, submission, or processing through the Service of Protected Health Information and other regulated health data.
  - summary: No classified government information
    text: Process documents containing classified, top-secret, or restricted government information without proper authorization and security clearance
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
name: justfill-app
provenance_date: '2026-11-09'
provider_name: justfill-app
provider_slug: justfill-app
slug: justfill-app-eligibility
source_date: '2026-11-09'
source_filename: justfill-app-eligibility.yml
source_heading: Eligibility
source_page: https://justfill.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: justfill-app\naid: justfill-app\nurl: https://justfill.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to create a JustFill account and use the Service.\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization to these Terms.\nrestricted_uses:\n- summary: No PHI or regulated health data\n  text: This Section 4E sets forth an absolute prohibition on the upload,\
  \ submission, or processing through the\n    Service of Protected Health Information and other regulated health data.\n- summary: No classified government information\n  text: Process documents containing classified, top-secret, or restricted government information without proper\n    authorization and security clearance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create a JustFill account and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/justfill-app/eligibility/justfill-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from justfill-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- PDF
- Form Filling
- Software-as-a-Service
---
