---
api_specs:
- filename: unipile-com-accounts-api-openapi.yml
  format: yaml
  label: unipile-com Accounts API
  slug: unipile-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-accounts-api-openapi.yml
- filename: unipile-com-calendars-api-openapi.yml
  format: yaml
  label: unipile-com Calendars API
  slug: unipile-com-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-calendars-api-openapi.yml
- filename: unipile-com-emails-api-openapi.yml
  format: yaml
  label: unipile-com Emails API
  slug: unipile-com-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-emails-api-openapi.yml
- filename: unipile-com-linkedin-specific-api-openapi.yml
  format: yaml
  label: unipile-com LinkedIn Specific API
  slug: unipile-com-linkedin-specific-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-linkedin-specific-api-openapi.yml
- filename: unipile-com-messaging-api-openapi.yml
  format: yaml
  label: unipile-com Messaging API
  slug: unipile-com-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-messaging-api-openapi.yml
- filename: unipile-com-posts-api-openapi.yml
  format: yaml
  label: unipile-com Posts API
  slug: unipile-com-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-posts-api-openapi.yml
- filename: unipile-com-users-api-openapi.yml
  format: yaml
  label: unipile-com Users API
  slug: unipile-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-users-api-openapi.yml
- filename: unipile-com-webhooks-api-openapi.yml
  format: yaml
  label: unipile-com Webhooks API
  slug: unipile-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unipile-com/openapi/unipile-com-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use our services.
    type: individual
  - text: The Services are intended for professional and commercial use, including integration into software applications, SaaS platforms, and other products developed by the User.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use our services.
    value: '18'
  restricted_uses:
  - summary: Illegal, fraudulent or abusive purposes
    text: Any use of the services for illegal, fraudulent, or abusive purposes is strictly prohibited.
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
name: unipile-com
provenance_date: '2026-11-10'
provider_name: unipile-com
provider_slug: unipile-com
slug: unipile-com-eligibility
source_date: '2026-11-10'
source_filename: unipile-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.unipile.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: unipile-com\naid: unipile-com\nurl: https://www.unipile.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use our services.\n- type: business\n  text: The Services are intended for professional and commercial use, including integration into software applications,\n    SaaS platforms, and other products developed by the User.\nrestricted_uses:\n- summary: Illegal, fraudulent or abusive purposes\n  text: Any use of the services for illegal, fraudulent, or abusive purposes is strictly\
  \ prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use our services.\n"
source_yaml_url: https://artifacts.apis.io/unipile-com/eligibility/unipile-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from unipile-com's own page on 2026-11-10.
synthetic: false
tags:
- Messaging
- Integration
- Multi-Channel
- Communications
---
