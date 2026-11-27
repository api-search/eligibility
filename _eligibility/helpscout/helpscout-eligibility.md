---
api_specs:
- filename: helpscout-conversations-api-openapi.yml
  format: yaml
  label: Help Scout Conversations API
  slug: helpscout-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-conversations-api-openapi.yml
- filename: helpscout-customers-api-openapi.yml
  format: yaml
  label: Help Scout Customers API
  slug: helpscout-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-customers-api-openapi.yml
- filename: helpscout-mailboxes-api-openapi.yml
  format: yaml
  label: Help Scout Mailboxes API
  slug: helpscout-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-mailboxes-api-openapi.yml
- filename: helpscout-tags-api-openapi.yml
  format: yaml
  label: Help Scout Tags API
  slug: helpscout-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-tags-api-openapi.yml
- filename: helpscout-teams-api-openapi.yml
  format: yaml
  label: Help Scout Teams API
  slug: helpscout-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-teams-api-openapi.yml
- filename: helpscout-threads-api-openapi.yml
  format: yaml
  label: Help Scout Threads API
  slug: helpscout-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-threads-api-openapi.yml
- filename: helpscout-users-api-openapi.yml
  format: yaml
  label: Help Scout Users API
  slug: helpscout-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-users-api-openapi.yml
- filename: helpscout-webhooks-api-openapi.yml
  format: yaml
  label: Help Scout Webhooks API
  slug: helpscout-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-webhooks-api-openapi.yml
- filename: helpscout-workflows-api-openapi.yml
  format: yaml
  label: Help Scout Workflows API
  slug: helpscout-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/helpscout/openapi/helpscout-workflows-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are intended for use by individuals 18 years of age and older.
    type: individual
  - text: if you are accessing or using the Services on behalf of another individual, organization, or entity (“Entity”), that Entity (in either case, “Customer”)
    type: business
  minimum_age:
    text: By accessing or using the Platform, you represent and warrant that you are at least 18 years of age.
    value: '18'
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
name: Help Scout
provenance_date: '2026-11-09'
provider_name: Help Scout
provider_slug: helpscout
slug: helpscout-eligibility
source_date: '2026-11-09'
source_filename: helpscout-eligibility.yml
source_heading: Eligibility
source_page: https://www.helpscout.com/company/legal/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Help Scout\naid: helpscout\nurl: https://www.helpscout.com/company/legal/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are intended for use by individuals 18 years of age and older.\n- type: business\n  text: if you are accessing or using the Services on behalf of another individual, organization, or entity (“Entity”),\n    that Entity (in either case, “Customer”)\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ By accessing or using the Platform, you represent and warrant that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/helpscout/eligibility/helpscout-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Help Scout's own page on 2026-11-09.
synthetic: false
tags:
- Customer Service
- Help Desk
- Email
- Live Chat
- Knowledge Base
- Software-as-a-Service
---
