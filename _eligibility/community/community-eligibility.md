---
api_specs:
- filename: community-member-data-api-openapi.yml
  format: yaml
  label: Community Member Data API
  slug: community-member-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/community/openapi/community-member-data-api-openapi.yml
- filename: community-messaging-api-openapi.yml
  format: yaml
  label: Community Messaging API
  slug: community-messaging-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/community/openapi/community-messaging-api-openapi.yml
- filename: community-tags-api-openapi.yml
  format: yaml
  label: Community Tags API
  slug: community-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/community/openapi/community-tags-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We may limit Community's availability at any time, in whole or in part, to any person, geographic area, or jurisdiction.
  entity_types:
  - text: Community's Service is designed solely for businesses, and not for consumers, and that purchase and use of Community's Service constitutes a business-to-business transaction.
    type: business
  minimum_age:
    text: if you are under the age of 13 or are under the age of majority in your jurisdiction, whichever is greater
    value: 13 or age of majority, whichever is greater
  restricted_uses:
  - summary: Export and embargo restrictions
    text: 'You represent, warrant, and covenant that you are not: (i) located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to be able to receive or send SMS messages, you will be required to register your ten-digit phone number with our carrier via your Community account (A2P Registration).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Community
provenance_date: '2026-11-09'
provider_name: Community
provider_slug: community
slug: community-eligibility
source_date: '2026-11-09'
source_filename: community-eligibility.yml
source_heading: Eligibility
source_page: https://community.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Community\naid: community\nurl: https://community.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We may limit Community's availability at any time, in whole or in part, to any person, geographic area,\n    or jurisdiction.\nentity_types:\n- type: business\n  text: Community's Service is designed solely for businesses, and not for consumers, and that purchase and use\n    of Community's Service constitutes a business-to-business transaction.\nrestricted_uses:\n- summary: Export and embargo restrictions\n  text: 'You represent, warrant, and covenant that you are not:\
  \ (i) located in, or a resident or a national of,\n    any country subject to a U.S. government embargo or other restriction'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to be able to receive or send SMS messages, you will be required to register your ten-digit phone\n    number with our carrier via your Community account (A2P Registration).\nminimum_age:\n  value: 13 or age of majority, whichever is greater\n  text: if you are under the age of 13 or are under the age of majority in your jurisdiction, whichever is greater\n"
source_yaml_url: https://artifacts.apis.io/community/eligibility/community-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Community's own page on 2026-11-09.
synthetic: false
tags:
- Messaging
- SMS
- Communications
- Marketing
- Creators
- Webhook
- Company
---
