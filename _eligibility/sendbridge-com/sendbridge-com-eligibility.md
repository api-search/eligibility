---
api_specs:
- filename: sendbridge-com-account-api-openapi.yml
  format: yaml
  label: SendBridge Account API
  slug: sendbridge-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbridge-com/openapi/sendbridge-com-account-api-openapi.yml
- filename: sendbridge-com-dmarc-api-openapi.yml
  format: yaml
  label: SendBridge DMARC API
  slug: sendbridge-com-dmarc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbridge-com/openapi/sendbridge-com-dmarc-api-openapi.yml
- filename: sendbridge-com-mail-tester-api-openapi.yml
  format: yaml
  label: SendBridge Mail Tester API
  slug: sendbridge-com-mail-tester-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbridge-com/openapi/sendbridge-com-mail-tester-api-openapi.yml
- filename: sendbridge-com-validation-api-openapi.yml
  format: yaml
  label: SendBridge Validation API
  slug: sendbridge-com-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendbridge-com/openapi/sendbridge-com-validation-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'In order to use sendbridge.com, you must: be at least eighteen (18) years old and able to enter into contracts'
    type: individual
  - text: If you sign up for sendbridge.com on behalf of a company or other entity, you represent and warrant that you have the authority to accept these Terms on their behalf.
    type: business
  minimum_age:
    text: be at least eighteen (18) years old and able to enter into contracts
    value: '18'
  restricted_uses:
  - summary: Spam and violating laws
    text: You represent and warrant that your use of sendbridge.com will comply with all applicable laws and regulations.
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
name: SendBridge
provenance_date: '2026-11-10'
provider_name: SendBridge
provider_slug: sendbridge-com
slug: sendbridge-com-eligibility
source_date: '2026-11-10'
source_filename: sendbridge-com-eligibility.yml
source_heading: Eligibility
source_page: https://sendbridge.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SendBridge\naid: sendbridge-com\nurl: https://sendbridge.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'In order to use sendbridge.com, you must: be at least eighteen (18) years old and able to enter into contracts'\n- type: business\n  text: If you sign up for sendbridge.com on behalf of a company or other entity, you represent and warrant that\n    you have the authority to accept these Terms on their behalf.\nrestricted_uses:\n- summary: Spam and violating laws\n  text: You represent and warrant that your use of sendbridge.com\
  \ will comply with all applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least eighteen (18) years old and able to enter into contracts\n"
source_yaml_url: https://artifacts.apis.io/sendbridge-com/eligibility/sendbridge-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SendBridge's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Verification
- Deliverability
- Validation
- Marketing
- Services
---
