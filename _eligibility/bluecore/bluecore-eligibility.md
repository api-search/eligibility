---
api_specs:
- filename: bluecore-authn-api-openapi.yml
  format: yaml
  label: Bluecore Authn API
  slug: bluecore-authn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bluecore/openapi/bluecore-authn-api-openapi.yml
- filename: bluecore-campaignsapipublic-api-openapi.yml
  format: yaml
  label: Bluecore CampaignsAPIPublic API
  slug: bluecore-campaignsapipublic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bluecore/openapi/bluecore-campaignsapipublic-api-openapi.yml
- filename: bluecore-direct-send-api-openapi.yml
  format: yaml
  label: Bluecore Direct send API
  slug: bluecore-direct-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bluecore/openapi/bluecore-direct-send-api-openapi.yml
- filename: bluecore-eligibility-api-openapi.yml
  format: yaml
  label: Bluecore Eligibility API
  slug: bluecore-eligibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bluecore/openapi/bluecore-eligibility-api-openapi.yml
- filename: bluecore-profile-api-openapi.yml
  format: yaml
  label: Bluecore Profile API
  slug: bluecore-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bluecore/openapi/bluecore-profile-api-openapi.yml
- filename: bluecore-transactional-api-openapi.yml
  format: yaml
  label: Bluecore Transactional API
  slug: bluecore-transactional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bluecore/openapi/bluecore-transactional-api-openapi.yml
- filename: bluecore-get-status-api-openapi.yml
  format: yaml
  label: Bluecore GET STATUS API
  slug: bluecore-get-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bluecore/openapi/bluecore-get-status-api-openapi.yml
- filename: bluecore-send-email-api-openapi.yml
  format: yaml
  label: Bluecore SEND EMAIL API
  slug: bluecore-send-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bluecore/openapi/bluecore-send-email-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Site on behalf of a company, entity, or organization, you represent and warrant that you are an authorized representative of such company, entity, or organization
    type: business
  minimum_age:
    text: you represent and warrant that you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: No sending of SMS-delivered email or unsolicited messages
    text: (g) send marketing or commercial email without permission; (h) upload or send to purchased lists, rented lists or third-party lists of any kind
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
name: Bluecore
provenance_date: '2026-11-09'
provider_name: Bluecore
provider_slug: bluecore
slug: bluecore-eligibility
source_date: '2026-11-09'
source_filename: bluecore-eligibility.yml
source_heading: Eligibility
source_page: https://www.bluecore.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bluecore\naid: bluecore\nurl: https://www.bluecore.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Site on behalf of a company, entity, or organization, you represent and warrant that\n    you are an authorized representative of such company, entity, or organization\nrestricted_uses:\n- summary: No sending of SMS-delivered email or unsolicited messages\n  text: (g) send marketing or commercial email without permission; (h) upload or send to purchased lists, rented\n    lists or third-party lists\
  \ of any kind\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/bluecore/eligibility/bluecore-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bluecore's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Retail
- Marketing
- Customer Data Platform
- Personalization
- Email
- SMS
- Messaging
- E-Commerce
- Consent
---
