---
api_specs:
- filename: agechecker-net-sessions-api-openapi.yml
  format: yaml
  label: AgeChecker.Net Sessions API
  slug: agechecker-net-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agechecker-net/openapi/agechecker-net-sessions-api-openapi.yml
- filename: agechecker-net-verification-api-openapi.yml
  format: yaml
  label: AgeChecker.Net Verification API
  slug: agechecker-net-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agechecker-net/openapi/agechecker-net-verification-api-openapi.yml
- filename: agechecker-net-webhooks-api-openapi.yml
  format: yaml
  label: AgeChecker.Net Webhooks API
  slug: agechecker-net-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agechecker-net/openapi/agechecker-net-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform and Services are intended for business use only and are not offered to consumers for personal, family, or household purposes.
    type: business
  minimum_age:
    text: the person accepting this Agreement must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No credit/employment eligibility use (FCRA)
    text: Customer must not use the Services or information obtained through the Services, in whole or in part, as a factor in establishing any individual's eligibility for credit, insurance, employment
  - summary: Customer responsible for regulated products
    text: Customer is solely responsible for determining whether Customer's products or services are lawful in each jurisdiction where Customer offers them
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
name: AgeChecker.Net
provenance_date: '2026-11-09'
provider_name: AgeChecker.Net
provider_slug: agechecker-net
slug: agechecker-net-eligibility
source_date: '2026-11-09'
source_filename: agechecker-net-eligibility.yml
source_heading: Eligibility
source_page: https://agechecker.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgeChecker.Net\naid: agechecker-net\nurl: https://agechecker.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Platform and Services are intended for business use only and are not offered to consumers for personal,\n    family, or household purposes.\nrestricted_uses:\n- summary: No credit/employment eligibility use (FCRA)\n  text: Customer must not use the Services or information obtained through the Services, in whole or in part, as\n    a factor in establishing any individual's eligibility for credit,\
  \ insurance, employment\n- summary: Customer responsible for regulated products\n  text: Customer is solely responsible for determining whether Customer's products or services are lawful in each\n    jurisdiction where Customer offers them\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the person accepting this Agreement must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/agechecker-net/eligibility/agechecker-net-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AgeChecker.Net's own page on 2026-11-09.
synthetic: false
tags:
- Age Verification
- Identity
- Compliance
- Regulatory
- E-Commerce
---
