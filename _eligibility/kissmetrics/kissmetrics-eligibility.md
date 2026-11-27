---
api_specs:
- filename: kissmetrics-products-api-openapi.yml
  format: yaml
  label: Kissmetrics REST API
  slug: rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kissmetrics/openapi/kissmetrics-products-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Export controls apply; embargoed countries may not use services.
  minimum_age:
    text: You must be at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Children's websites
    text: Services may not be used for websites labeled, described as, or directed at individuals under 13.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Complete registration requires providing your name, email, telephone, company name, website, and password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kissmetrics
provenance_date: '2026-11-09'
provider_name: Kissmetrics
provider_slug: kissmetrics
slug: kissmetrics-eligibility
source_date: '2026-11-09'
source_filename: kissmetrics-eligibility.yml
source_heading: Eligibility
source_page: https://kissmetrics.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kissmetrics\naid: kissmetrics\nurl: https://kissmetrics.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Export controls apply; embargoed countries may not use services.\nentity_types: []\nrestricted_uses:\n- summary: Children's websites\n  text: Services may not be used for websites labeled, described as, or directed at individuals under 13.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Complete registration requires providing your name, email, telephone, company name, website, and password.\nminimum_age:\n  value: '13'\n  text: You must be\
  \ at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/kissmetrics/eligibility/kissmetrics-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Kissmetrics's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Product Analytics
- Behavioral Analytics
- Marketing Analytics
- Customer Analytics
- Event Tracking
- Funnels
- Cohorts
- Retention
- Attribution
- Data Export
---
