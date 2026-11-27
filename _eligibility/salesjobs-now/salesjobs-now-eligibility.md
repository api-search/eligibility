---
api_specs:
- filename: salesjobs-now-jobs-api-openapi.yml
  format: yaml
  label: SalesJobs.Now Jobs API
  slug: salesjobs-now-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesjobs-now/openapi/salesjobs-now-jobs-api-openapi.yml
- filename: salesjobs-now-pay-csv-api-openapi.yml
  format: yaml
  label: SalesJobs.Now Pay.csv API
  slug: salesjobs-now-pay-csv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesjobs-now/openapi/salesjobs-now-pay-csv-api-openapi.yml
- filename: salesjobs-now-pay-json-api-openapi.yml
  format: yaml
  label: SalesJobs.Now Pay.json API
  slug: salesjobs-now-pay-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesjobs-now/openapi/salesjobs-now-pay-json-api-openapi.yml
- filename: salesjobs-now-roles-json-api-openapi.yml
  format: yaml
  label: SalesJobs.Now Roles.json API
  slug: salesjobs-now-roles-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesjobs-now/openapi/salesjobs-now-roles-json-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Service if you can enter a binding contract and you keep to these Terms and the law.
    type: individual
  - text: If you use the Service for an employer, an agency or another organisation, you confirm that you may bind it to these Terms, and "you" then means that organisation.
    type: business
  minimum_age:
    text: You must be at least the age your country sets for consenting to the processing of your personal data, or the age of majority where that is higher.
    value: Age of consent for personal data or age of majority
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
name: SalesJobs.Now
provenance_date: '2026-11-10'
provider_name: SalesJobs.Now
provider_slug: salesjobs-now
slug: salesjobs-now-eligibility
source_date: '2026-11-10'
source_filename: salesjobs-now-eligibility.yml
source_heading: Eligibility
source_page: https://salesjobs.now/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SalesJobs.Now\naid: salesjobs-now\nurl: https://salesjobs.now/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Service if you can enter a binding contract and you keep to these Terms and the law.\n- type: business\n  text: If you use the Service for an employer, an agency or another organisation, you confirm that you may bind\n    it to these Terms, and \"you\" then means that organisation.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: Age of consent for personal data or age of majority\n  text: You must be at least the age your country sets for consenting to the processing of your personal data, or\n    the age of majority where that is higher.\n"
source_yaml_url: https://artifacts.apis.io/salesjobs-now/eligibility/salesjobs-now-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from SalesJobs.Now's own page on 2026-11-10.
synthetic: false
tags:
- Sales
- Job
- Recruiting
- Data
---
