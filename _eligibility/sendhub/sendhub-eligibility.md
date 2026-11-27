---
api_specs:
- filename: sendhub-authentication-api-openapi.yml
  format: yaml
  label: SendHub Authentication API
  slug: sendhub-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhub/openapi/sendhub-authentication-api-openapi.yml
- filename: sendhub-contact-api-openapi.yml
  format: yaml
  label: SendHub Contact API
  slug: sendhub-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhub/openapi/sendhub-contact-api-openapi.yml
- filename: sendhub-group-api-openapi.yml
  format: yaml
  label: SendHub Group API
  slug: sendhub-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhub/openapi/sendhub-group-api-openapi.yml
- filename: sendhub-message-api-openapi.yml
  format: yaml
  label: SendHub Message API
  slug: sendhub-message-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhub/openapi/sendhub-message-api-openapi.yml
- filename: sendhub-profile-api-openapi.yml
  format: yaml
  label: SendHub Profile API
  slug: sendhub-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhub/openapi/sendhub-profile-api-openapi.yml
- filename: sendhub-thread-api-openapi.yml
  format: yaml
  label: SendHub Thread API
  slug: sendhub-thread-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendhub/openapi/sendhub-thread-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: These services can be used from or accessed in the 48 contiguous states or Canada
  minimum_age:
    text: You may only use the Site and services provided by the Site given the fact that You are not less than 13 years of age
    value: '13'
  restricted_uses:
  - summary: Spam and unsolicited messages
    text: SendHub maintains a zero tolerance policy regarding the delivery of Spam or unwanted commercial messages using the Service.
  - summary: Certain calls not permitted
    text: You cannot use the Service to place certain calls, which include but are not limited to international, 1-900 or other toll calls, 911
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
name: SendHub
provenance_date: '2026-11-10'
provider_name: SendHub
provider_slug: sendhub
slug: sendhub-eligibility
source_date: '2026-11-10'
source_filename: sendhub-eligibility.yml
source_heading: Eligibility
source_page: https://www.sendhub.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SendHub\naid: sendhub\nurl: https://www.sendhub.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: These services can be used from or accessed in the 48 contiguous states or Canada\nentity_types: []\nrestricted_uses:\n- summary: Spam and unsolicited messages\n  text: SendHub maintains a zero tolerance policy regarding the delivery of Spam or unwanted commercial messages\n    using the Service.\n- summary: Certain calls not permitted\n  text: You cannot use the Service to place certain calls, which include but are not limited to international, 1-900\n \
  \   or other toll calls, 911\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may only use the Site and services provided by the Site given the fact that You are not less than 13\n    years of age\n"
source_yaml_url: https://artifacts.apis.io/sendhub/eligibility/sendhub-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SendHub's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Messaging
- Text Messaging
- Communications
- Marketing
- Webhook
- VoIP
---
