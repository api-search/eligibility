---
api_specs:
- filename: paubox-analytics-api-openapi.yml
  format: yaml
  label: Paubox Analytics API
  slug: paubox-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-analytics-api-openapi.yml
- filename: paubox-campaign-mailings-api-openapi.yml
  format: yaml
  label: Paubox Campaign Mailings API
  slug: paubox-campaign-mailings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-campaign-mailings-api-openapi.yml
- filename: paubox-drip-campaigns-api-openapi.yml
  format: yaml
  label: Paubox Drip Campaigns API
  slug: paubox-drip-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-drip-campaigns-api-openapi.yml
- filename: paubox-dynamic-templates-api-openapi.yml
  format: yaml
  label: Paubox Dynamic Templates API
  slug: paubox-dynamic-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-dynamic-templates-api-openapi.yml
- filename: paubox-form-management-api-openapi.yml
  format: yaml
  label: Paubox Form management API
  slug: paubox-form-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-form-management-api-openapi.yml
- filename: paubox-forms-api-openapi.yml
  format: yaml
  label: Paubox Forms API
  slug: paubox-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-forms-api-openapi.yml
- filename: paubox-messages-api-openapi.yml
  format: yaml
  label: Paubox Messages API
  slug: paubox-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-messages-api-openapi.yml
- filename: paubox-submissions-api-openapi.yml
  format: yaml
  label: Paubox Submissions API
  slug: paubox-submissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-submissions-api-openapi.yml
- filename: paubox-subscribers-api-openapi.yml
  format: yaml
  label: Paubox Subscribers API
  slug: paubox-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscribers-api-openapi.yml
- filename: paubox-subscription-lists-api-openapi.yml
  format: yaml
  label: Paubox Subscription Lists API
  slug: paubox-subscription-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscription-lists-api-openapi.yml
- filename: paubox-subscriptions-api-openapi.yml
  format: yaml
  label: Paubox Subscriptions API
  slug: paubox-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-subscriptions-api-openapi.yml
- filename: paubox-tracking-links-api-openapi.yml
  format: yaml
  label: Paubox Tracking Links API
  slug: paubox-tracking-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paubox/openapi/paubox-tracking-links-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE AS AN INDIVIDUAL, THE TERM “CUSTOMER” REFERS TO YOU.
    type: individual
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with laws
    text: Customer represents and warrants that Customer will use the Services only for its intended use and in compliance with applicable laws and regulations.
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
name: Paubox
provenance_date: '2026-11-10'
provider_name: Paubox
provider_slug: paubox
slug: paubox-eligibility
source_date: '2026-11-10'
source_filename: paubox-eligibility.yml
source_heading: Eligibility
source_page: https://www.paubox.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paubox\naid: paubox\nurl: https://www.paubox.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: IF YOU ARE ENTERING INTO THESE TERMS OF SERVICE AS AN INDIVIDUAL, THE TERM “CUSTOMER” REFERS TO YOU.\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY\nrestricted_uses:\n- summary: Compliance with laws\n  text: Customer represents and warrants that Customer will use the Services only for its\
  \ intended use and in compliance\n    with applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paubox/eligibility/paubox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Paubox's own page on 2026-11-10.
synthetic: false
tags:
- Email
- HIPAA
- Healthcare
- Compliance
- Transactional Email
- Email Marketing
- Forms
- Security
- Encryption
- Messaging
- A2A
---
