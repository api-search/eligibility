---
api_specs:
- filename: weave-contacts-api-openapi.yml
  format: yaml
  label: Weave Contacts API
  slug: weave-hq-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-contacts-api-openapi.yml
- filename: weave-events-api-openapi.yml
  format: yaml
  label: Weave Events API
  slug: weave-hq-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-events-api-openapi.yml
- filename: weave-forms-api-openapi.yml
  format: yaml
  label: Weave Forms API
  slug: weave-hq-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-forms-api-openapi.yml
- filename: weave-messaging-api-openapi.yml
  format: yaml
  label: Weave Messaging API
  slug: weave-hq-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-messaging-api-openapi.yml
- filename: weave-payments-api-openapi.yml
  format: yaml
  label: Weave Payments API
  slug: weave-hq-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-payments-api-openapi.yml
- filename: weave-phone-calls-api-openapi.yml
  format: yaml
  label: Weave Phone & Calls API
  slug: weave-hq-phone-calls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-phone-calls-api-openapi.yml
- filename: weave-reviews-api-openapi.yml
  format: yaml
  label: Weave Reviews API
  slug: weave-hq-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-reviews-api-openapi.yml
- filename: weave-scheduling-api-openapi.yml
  format: yaml
  label: Weave Scheduling API
  slug: weave-hq-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weave/openapi/weave-scheduling-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States and Canada.
  entity_types:
  - text: the representative who is authorized to legally bind a single company, organization, or entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or restricted use
    text: You agree to not use the software or offer services, product, or content, that is deemed unlawful or restricted by any Governmental Authority or Weave
  - source: https://www.getweave.com/legal/payments/
    summary: Restricted businesses and sanctioned parties
    text: Restricted businesses or activities include use of the Payments Service in or for the benefit of a country, organization, entity, or person embargoed or blocked by any government
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
name: Weave
provenance_date: '2026-11-10'
provider_name: Weave
provider_slug: weave
slug: weave-eligibility
source_date: '2026-11-10'
source_filename: weave-eligibility.yml
source_heading: Eligibility
source_page: https://www.getweave.com/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Weave\naid: weave\nurl: https://www.getweave.com/legal/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://www.getweave.com/legal/payments/\n  - https://www.getweave.com/legal/terms/\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States and Canada.\nentity_types:\n- type: business\n  text: the representative who is authorized to legally bind a single company, organization, or entity\nrestricted_uses:\n- summary:\
  \ Unlawful or restricted use\n  text: You agree to not use the software or offer services, product, or content, that is deemed unlawful or restricted\n    by any Governmental Authority or Weave\n- summary: Restricted businesses and sanctioned parties\n  text: Restricted businesses or activities include use of the Payments Service in or for the benefit of a country,\n    organization, entity, or person embargoed or blocked by any government\n  source: https://www.getweave.com/legal/payments/\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/weave/eligibility/weave-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Weave's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Messaging
- Payments
- Healthcare
- VoIP
- Telephony
- Reviews
- Scheduling
- Small Business
- Developer Platform
- OAuth
- Authentication
---
