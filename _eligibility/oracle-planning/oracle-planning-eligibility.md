---
api_specs:
- filename: openapi.json
  format: json
  label: Oracle Planning REST API
  slug: oracle-planning-rest-api
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/planning-budgeting-cloud/rest/openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Oracle reserves the right to make products available in some locations; no country-level eligibility list stated.
  minimum_age:
    text: Persons who are not of the age of majority are not eligible to use the Site
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You may not access, download, use or export the Site, or the Content provided on or through the Site, in violation of U.S. export laws or regulations
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
name: Oracle Planning
provenance_date: '2026-11-10'
provider_name: Oracle Planning
provider_slug: oracle-planning
slug: oracle-planning-eligibility
source_date: '2026-11-10'
source_filename: oracle-planning-eligibility.yml
source_heading: Eligibility
source_page: https://www.oracle.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oracle Planning\naid: oracle-planning\nurl: https://www.oracle.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Oracle reserves the right to make products available in some locations; no country-level eligibility list\n    stated.\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You may not access, download, use or export the Site, or the Content provided on or through the Site, in\n    violation of U.S. export laws or regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Persons who are not of the age of majority are not eligible to use the Site\n"
source_yaml_url: https://artifacts.apis.io/oracle-planning/eligibility/oracle-planning-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Oracle Planning's own page on 2026-11-10.
synthetic: false
tags:
- Budgeting
- Cloud
- Consolidation
- Enterprise
- EPM
- Financial Close
- Financial Planning
- Forecasting
- Oracle
- Planning
---
