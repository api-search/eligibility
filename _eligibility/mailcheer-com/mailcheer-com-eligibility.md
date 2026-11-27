---
api_specs:
- filename: mailcheer-com-campaigns-api-openapi.yml
  format: yaml
  label: mailcheer-com Campaigns API
  slug: mailcheer-com-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-campaigns-api-openapi.yml
- filename: mailcheer-com-emails-api-openapi.yml
  format: yaml
  label: mailcheer-com Emails API
  slug: mailcheer-com-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-emails-api-openapi.yml
- filename: mailcheer-com-subscribers-api-openapi.yml
  format: yaml
  label: mailcheer-com Subscribers API
  slug: mailcheer-com-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-subscribers-api-openapi.yml
- filename: mailcheer-com-suppression-api-openapi.yml
  format: yaml
  label: mailcheer-com Suppression API
  slug: mailcheer-com-suppression-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-suppression-api-openapi.yml
- filename: mailcheer-com-webhooks-api-openapi.yml
  format: yaml
  label: mailcheer-com Webhooks API
  slug: mailcheer-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-webhooks-api-openapi.yml
- filename: mailcheer-com-workspace-api-openapi.yml
  format: yaml
  label: mailcheer-com Workspace API
  slug: mailcheer-com-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-workspace-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The service is intended for professionals (companies, sole traders, associations) and individuals alike.
    type: business
  - text: The service is intended for professionals (companies, sole traders, associations) and individuals alike.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Opt-in or existing-relationship consent required
    text: You may only send emails to people who have explicitly consented (opt-in) or with whom you have an existing customer relationship, in compliance with the GDPR
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
name: mailcheer-com
provenance_date: '2026-11-10'
provider_name: mailcheer-com
provider_slug: mailcheer-com
slug: mailcheer-com-eligibility
source_date: '2026-11-10'
source_filename: mailcheer-com-eligibility.yml
source_heading: Eligibility
source_page: https://mailcheer.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: mailcheer-com\naid: mailcheer-com\nurl: https://mailcheer.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The service is intended for professionals (companies, sole traders, associations) and individuals alike.\n- type: individual\n  text: The service is intended for professionals (companies, sole traders, associations) and individuals alike.\nrestricted_uses:\n- summary: Opt-in or existing-relationship consent required\n  text: You may only send emails to people who have explicitly consented (opt-in) or with whom you have\
  \ an existing\n    customer relationship, in compliance with the GDPR\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mailcheer-com/eligibility/mailcheer-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from mailcheer-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Newsletters
- Marketing
- Artificial Intelligence
---
