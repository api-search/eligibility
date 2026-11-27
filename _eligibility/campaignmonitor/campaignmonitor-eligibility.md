---
api_specs:
- filename: campaignmonitor-openapi-generated.yml
  format: yaml
  label: Campaign Monitor API
  slug: campaignmonitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campaignmonitor/openapi/_ae-authored/campaignmonitor-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'In order to use the Services, You must: be at least 18 years old; complete the registration process; agree to this Agreement; and provide true, complete, and up to date contact information.'
    type: individual
  - text: If You enter into this Agreement or acquire the Services on behalf of an entity, You represent and warrant that You have the authority to accept this Agreement on the entity's behalf.
    type: business
  minimum_age:
    text: be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Sensitive PII prohibited
    text: Customer agrees not to, and not to permit Users to, transmit, request, provide Company with access to, submit, store, or include any Sensitive PII through the Services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company may refuse to provide You with the Services, suspend or close Your account, and change eligibility requirements at any time in accordance with the terms of this Agreement.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Campaign Monitor
provenance_date: '2026-11-09'
provider_name: Campaign Monitor
provider_slug: campaignmonitor
slug: campaignmonitor-eligibility
source_date: '2026-11-09'
source_filename: campaignmonitor-eligibility.yml
source_heading: Eligibility
source_page: https://www.campaignmonitor.com/policies/#terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Campaign Monitor\naid: campaignmonitor\nurl: https://www.campaignmonitor.com/policies/#terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'In order to use the Services, You must: be at least 18 years old; complete the registration process; agree\n    to this Agreement; and provide true, complete, and up to date contact information.'\n- type: business\n  text: If You enter into this Agreement or acquire the Services on behalf of an entity, You represent and warrant\n    that You have the authority to accept\
  \ this Agreement on the entity's behalf.\nrestricted_uses:\n- summary: Sensitive PII prohibited\n  text: Customer agrees not to, and not to permit Users to, transmit, request, provide Company with access to, submit,\n    store, or include any Sensitive PII through the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Company may refuse to provide You with the Services, suspend or close Your account, and change eligibility\n    requirements at any time in accordance with the terms of this Agreement.\nminimum_age:\n  value: '18'\n  text: be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/campaignmonitor/eligibility/campaignmonitor-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Campaign Monitor's own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Campaigns
- Subscribers
- Transactional Email
- Segments
- Newsletters
- Automation
- Marketing Automation
- Webhook
- Email Deliverability
- Marketing
---
