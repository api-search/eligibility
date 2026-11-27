---
api_specs:
- filename: teamleader-contacts-api-openapi.yml
  format: yaml
  label: Teamleader Contacts API
  slug: teamleader-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-contacts-api-openapi.yml
- filename: teamleader-daysoff-api-openapi.yml
  format: yaml
  label: Teamleader Daysoff API
  slug: teamleader-daysoff-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-daysoff-api-openapi.yml
- filename: teamleader-deals-api-openapi.yml
  format: yaml
  label: Teamleader Deals API
  slug: teamleader-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-deals-api-openapi.yml
- filename: teamleader-expenses-api-openapi.yml
  format: yaml
  label: Teamleader Expenses API
  slug: teamleader-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-expenses-api-openapi.yml
- filename: teamleader-files-api-openapi.yml
  format: yaml
  label: Teamleader Files API
  slug: teamleader-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-files-api-openapi.yml
- filename: teamleader-invoices-api-openapi.yml
  format: yaml
  label: Teamleader Invoices API
  slug: teamleader-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-invoices-api-openapi.yml
- filename: teamleader-leveltwoareas-api-openapi.yml
  format: yaml
  label: Teamleader Leveltwoareas API
  slug: teamleader-leveltwoareas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-leveltwoareas-api-openapi.yml
- filename: teamleader-lostreasons-api-openapi.yml
  format: yaml
  label: Teamleader Lostreasons API
  slug: teamleader-lostreasons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-lostreasons-api-openapi.yml
- filename: teamleader-tasks-api-openapi.yml
  format: yaml
  label: Teamleader Tasks API
  slug: teamleader-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-tasks-api-openapi.yml
- filename: teamleader-tickets-api-openapi.yml
  format: yaml
  label: Teamleader Tickets API
  slug: teamleader-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-tickets-api-openapi.yml
- filename: teamleader-ticketstatus-api-openapi.yml
  format: yaml
  label: Teamleader Ticketstatus API
  slug: teamleader-ticketstatus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-ticketstatus-api-openapi.yml
- filename: teamleader-timers-api-openapi.yml
  format: yaml
  label: Teamleader Timers API
  slug: teamleader-timers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-timers-api-openapi.yml
- filename: teamleader-useravailability-api-openapi.yml
  format: yaml
  label: Teamleader Useravailability API
  slug: teamleader-useravailability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-useravailability-api-openapi.yml
- filename: teamleader-payment-methods-api-openapi.yml
  format: yaml
  label: Teamleader Payment Methods API
  slug: teamleader-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teamleader/openapi/teamleader-payment-methods-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: As the Services are solely meant for the Customer’s internal business purposes, any Customer is considered to be an ‘undertaking’ within the meaning of the Belgian Code of Economic Law and, consequently, cannot be a ‘consumer’ in its commercial relationship with TEAMLEADER.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive use
    text: Customer commits not to use the Tool to perform any activity which is or may be, directly or indirectly, unlawful, harmful, threatening, abusive, harassing, tortuous, or defamatory
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: At all times, TEAMLEADER shall be entitled to request additional information about the signatory and about the (potential) Customer.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Teamleader
provenance_date: '2026-11-10'
provider_name: Teamleader
provider_slug: teamleader
slug: teamleader-eligibility
source_date: '2026-11-10'
source_filename: teamleader-eligibility.yml
source_heading: Eligibility
source_page: https://www.teamleader.eu/legal/terms-of-service-teamleader-focus
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Teamleader\naid: teamleader\nurl: https://www.teamleader.eu/legal/terms-of-service-teamleader-focus\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: As the Services are solely meant for the Customer’s internal business purposes, any Customer is considered\n    to be an ‘undertaking’ within the meaning of the Belgian Code of Economic Law and, consequently, cannot be a\n    ‘consumer’ in its commercial relationship with TEAMLEADER.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: Customer commits not to\
  \ use the Tool to perform any activity which is or may be, directly or indirectly,\n    unlawful, harmful, threatening, abusive, harassing, tortuous, or defamatory\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: At all times, TEAMLEADER shall be entitled to request additional information about the signatory and about\n    the (potential) Customer.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/teamleader/eligibility/teamleader-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Teamleader's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Invoicing
- Project Management
- Software-as-a-Service
- Small Business
---
