---
api_specs:
- filename: onesignal-apps-api-openapi.yml
  format: yaml
  label: OneSignal Apps API
  slug: onesignal-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-apps-api-openapi.yml
- filename: onesignal-notifications-api-openapi.yml
  format: yaml
  label: OneSignal Notifications API
  slug: onesignal-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-notifications-api-openapi.yml
- filename: onesignal-players-api-openapi.yml
  format: yaml
  label: OneSignal Players API
  slug: onesignal-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-players-api-openapi.yml
- filename: onesignal-templates-api-openapi.yml
  format: yaml
  label: OneSignal Templates API
  slug: onesignal-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-templates-api-openapi.yml
- filename: onesignal-organizations-api-openapi.yml
  format: yaml
  label: OneSignal Organizations API
  slug: onesignal-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onesignal/openapi/onesignal-organizations-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: to the extent it is a corporation, it is duly incorporated and in good standing under the laws of the state of its incorporation
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited app content
    text: Licensee will not use the SDK in connection with any App that constitutes or promotes illegal gambling, adult media (i.e., pornography), inflammatory religious content, violence
  - summary: Children's apps (COPPA)
    text: OneSignal permits developers to use the service in applications “directed to children under 13” but Licensee must meet certain obligations
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
name: OneSignal
provenance_date: '2026-11-10'
provider_name: OneSignal
provider_slug: onesignal
slug: onesignal-eligibility
source_date: '2026-11-10'
source_filename: onesignal-eligibility.yml
source_heading: Eligibility
source_page: https://onesignal.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OneSignal\naid: onesignal\nurl: https://onesignal.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: to the extent it is a corporation, it is duly incorporated and in good standing under the laws of the state\n    of its incorporation\nrestricted_uses:\n- summary: Prohibited app content\n  text: Licensee will not use the SDK in connection with any App that constitutes or promotes illegal gambling,\n    adult media (i.e., pornography), inflammatory religious content, violence\n- summary: Children's apps (COPPA)\n  text: OneSignal\
  \ permits developers to use the service in applications “directed to children under 13” but Licensee\n    must meet certain obligations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onesignal/eligibility/onesignal-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from OneSignal's own page on 2026-11-10.
synthetic: false
tags:
- Notification
- Push
- Email
- SMS
- Mobile
- Push Notifications
- Web Push
- Customer Engagement
- Marketing Automation
- Live Activities
- RCS
- In-App Messaging
- Journeys
- Lifecycle Marketing
- MCP
- A2A
---
