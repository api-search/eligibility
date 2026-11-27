---
api_specs:
- filename: payments-canada-application-level-heartbeat-api-openapi.yml
  format: yaml
  label: Payments Canada application level heartbeat API
  slug: payments-canada-application-level-heartbeat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-application-level-heartbeat-api-openapi.yml
- filename: payments-canada-ccin-extract-resource-api-openapi.yml
  format: yaml
  label: Payments Canada Ccin Extract Resource API
  slug: payments-canada-ccin-extract-resource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-ccin-extract-resource-api-openapi.yml
- filename: payments-canada-fif-branches-resource-api-openapi.yml
  format: yaml
  label: Payments Canada Fif Branches Resource API
  slug: payments-canada-fif-branches-resource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-fif-branches-resource-api-openapi.yml
- filename: payments-canada-fif-extracts-resource-api-openapi.yml
  format: yaml
  label: Payments Canada Fif Extracts Resource API
  slug: payments-canada-fif-extracts-resource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-fif-extracts-resource-api-openapi.yml
- filename: payments-canada-interest-report-api-openapi.yml
  format: yaml
  label: Payments Canada Interest Report API
  slug: payments-canada-interest-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-interest-report-api-openapi.yml
- filename: payments-canada-master-extract-resource-api-openapi.yml
  format: yaml
  label: Payments Canada Master Extract Resource API
  slug: payments-canada-master-extract-resource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-master-extract-resource-api-openapi.yml
- filename: payments-canada-report-api-openapi.yml
  format: yaml
  label: Payments Canada Report API
  slug: payments-canada-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-report-api-openapi.yml
- filename: payments-canada-single-credit-transfer-api-openapi.yml
  format: yaml
  label: Payments Canada single credit transfer API
  slug: payments-canada-single-credit-transfer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-single-credit-transfer-api-openapi.yml
- filename: payments-canada-single-credit-transfer-status-enquiry-api-openapi.yml
  format: yaml
  label: Payments Canada single credit transfer status enquiry API
  slug: payments-canada-single-credit-transfer-status-enquiry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-single-credit-transfer-status-enquiry-api-openapi.yml
- filename: payments-canada-update-extract-resource-api-openapi.yml
  format: yaml
  label: Payments Canada Update Extract Resource API
  slug: payments-canada-update-extract-resource-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payments-canada/openapi/payments-canada-update-extract-resource-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Portal on behalf of another person, including a corporate entity, you confirm (1) that you have the authority to legally bind that person to these Terms
    type: business
  minimum_age:
    text: you are of majority age in the place you reside
    value: majority age
  restricted_uses:
  - summary: Services damaging to provider or members
    text: Use the Portal to create Apps that offer or promote services that may be damaging or otherwise detrimental to us or our members.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: After you have set up your Profile, we will allow you to access the Portal at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Payments Canada
provenance_date: '2026-11-10'
provider_name: Payments Canada
provider_slug: payments-canada
slug: payments-canada-eligibility
source_date: '2026-11-10'
source_filename: payments-canada-eligibility.yml
source_heading: Eligibility
source_page: https://developer.payments.ca/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Payments Canada\naid: payments-canada\nurl: https://developer.payments.ca/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Portal on behalf of another person, including a corporate entity, you confirm (1) that\n    you have the authority to legally bind that person to these Terms\nrestricted_uses:\n- summary: Services damaging to provider or members\n  text: Use the Portal to create Apps that offer or promote services that may be damaging or otherwise detrimental\n    to us or our members.\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: true\n  text: After you have set up your Profile, we will allow you to access the Portal at our discretion.\nminimum_age:\n  value: majority age\n  text: you are of majority age in the place you reside\n"
source_yaml_url: https://artifacts.apis.io/payments-canada/eligibility/payments-canada-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Payments Canada's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Payments
- Canada
- Payment Infrastructure
- Clearing and Settlement
- Real-Time Rail
- ISO 20022
- Lynx
- Crown Corporation
- Faster Payments
---
