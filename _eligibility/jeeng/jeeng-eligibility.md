---
api_specs:
- filename: jeeng-management-api-openapi.yml
  format: yaml
  label: Jeeng Management API
  slug: jeeng-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jeeng/openapi/jeeng-management-api-openapi.yml
- filename: jeeng-reporting-api-openapi.yml
  format: yaml
  label: Jeeng Reporting API
  slug: jeeng-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jeeng/openapi/jeeng-reporting-api-openapi.yml
- filename: jeeng-revenuestripe-onmicrosoft-com-api-openapi.yml
  format: yaml
  label: Jeeng Revenuestripe.onmicrosoft.com API
  slug: jeeng-revenuestripe-onmicrosoft-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jeeng/openapi/jeeng-revenuestripe-onmicrosoft-com-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are 18 years of age or older and have the ability to form a binding contract
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing use
    text: use the Services or content thereon in any unlawful or infringing manner or in any manner not permitted by these Terms
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Jeeng may refuse to open an account for any individual or entity at its sole discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Jeeng
provenance_date: '2026-11-09'
provider_name: Jeeng
provider_slug: jeeng
slug: jeeng-eligibility
source_date: '2026-11-09'
source_filename: jeeng-eligibility.yml
source_heading: Eligibility
source_page: https://www.jeeng.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jeeng\naid: jeeng\nurl: https://www.jeeng.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing use\n  text: use the Services or content thereon in any unlawful or infringing manner or in any manner not permitted\n    by these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Jeeng may refuse to open an account for any individual or entity at its sole discretion.\nminimum_age:\n  value: '18'\n  text: you are 18 years of age or older and have the ability to form\
  \ a binding contract\n"
source_yaml_url: https://artifacts.apis.io/jeeng/eligibility/jeeng-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Jeeng's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Advertising
- Publishing
- Email
- Push Notifications
- Monetization
- AdTech
- Newsletters
- Audience Engagement
- Reporting
- Analytics
- OData
- OAuth
- Authentication
---
