---
api_specs:
- filename: appsignal-openapi-generated.yml
  format: yaml
  label: AppSignal API
  slug: appsignal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsignal/openapi/_ae-authored/appsignal-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this agreement on behalf of a company or another legal entity, you affirm that you have the authority to bind such entity, its affiliates and all users who access the Service through your account to these Terms and Conditions.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sensitive data submission
    text: You are responsible for not submitting sensitive data to the Service, including but not limited to credit card information, medical files or anything deemed confidential.
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
name: AppSignal
provenance_date: '2026-11-09'
provider_name: AppSignal
provider_slug: appsignal
slug: appsignal-eligibility
source_date: '2026-11-09'
source_filename: appsignal-eligibility.yml
source_heading: Eligibility
source_page: https://www.appsignal.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppSignal\naid: appsignal\nurl: https://www.appsignal.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this agreement on behalf of a company or another legal entity, you affirm that\n    you have the authority to bind such entity, its affiliates and all users who access the Service through your\n    account to these Terms and Conditions.\nrestricted_uses:\n- summary: No sensitive data submission\n  text: You are responsible for not submitting sensitive data to the Service, including but not limited to\
  \ credit\n    card information, medical files or anything deemed confidential.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appsignal/eligibility/appsignal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from AppSignal's own page on 2026-11-09.
synthetic: false
tags:
- Monitoring
- Error Tracking
- Performance
- Observability
- Software-as-a-Service
---
