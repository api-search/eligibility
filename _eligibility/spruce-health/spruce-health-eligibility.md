---
api_specs:
- filename: spruce-health-contact-fields-api-openapi.yml
  format: yaml
  label: Spruce Health Contact Fields API
  slug: spruce-health-contact-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-contact-fields-api-openapi.yml
- filename: spruce-health-contact-tags-api-openapi.yml
  format: yaml
  label: Spruce Health Contact Tags API
  slug: spruce-health-contact-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-contact-tags-api-openapi.yml
- filename: spruce-health-contacts-api-openapi.yml
  format: yaml
  label: Spruce Health Contacts API
  slug: spruce-health-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-contacts-api-openapi.yml
- filename: spruce-health-conversation-item-api-openapi.yml
  format: yaml
  label: Spruce Health Conversation Item API
  slug: spruce-health-conversation-item-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-conversation-item-api-openapi.yml
- filename: spruce-health-conversation-tags-api-openapi.yml
  format: yaml
  label: Spruce Health Conversation Tags API
  slug: spruce-health-conversation-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-conversation-tags-api-openapi.yml
- filename: spruce-health-conversations-api-openapi.yml
  format: yaml
  label: Spruce Health Conversations API
  slug: spruce-health-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-conversations-api-openapi.yml
- filename: spruce-health-internal-endpoints-api-openapi.yml
  format: yaml
  label: Spruce Health Internal Endpoints API
  slug: spruce-health-internal-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-internal-endpoints-api-openapi.yml
- filename: spruce-health-media-api-openapi.yml
  format: yaml
  label: Spruce Health Media API
  slug: spruce-health-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-media-api-openapi.yml
- filename: spruce-health-organization-api-openapi.yml
  format: yaml
  label: Spruce Health Organization API
  slug: spruce-health-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-organization-api-openapi.yml
- filename: spruce-health-phone-lines-api-openapi.yml
  format: yaml
  label: Spruce Health Phone Lines API
  slug: spruce-health-phone-lines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-phone-lines-api-openapi.yml
- filename: spruce-health-saved-messages-api-openapi.yml
  format: yaml
  label: Spruce Health Saved Messages API
  slug: spruce-health-saved-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-saved-messages-api-openapi.yml
- filename: spruce-health-scheduled-messages-api-openapi.yml
  format: yaml
  label: Spruce Health Scheduled Messages API
  slug: spruce-health-scheduled-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-scheduled-messages-api-openapi.yml
- filename: spruce-health-teams-api-openapi.yml
  format: yaml
  label: Spruce Health Teams API
  slug: spruce-health-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-teams-api-openapi.yml
- filename: spruce-health-transcription-api-openapi.yml
  format: yaml
  label: Spruce Health Transcription API
  slug: spruce-health-transcription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-transcription-api-openapi.yml
- filename: spruce-health-webhooks-api-openapi.yml
  format: yaml
  label: Spruce Health Webhooks API
  slug: spruce-health-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spruce-health/openapi/spruce-health-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You understand that the Platform is intended for use only by entities that are subject exclusively to the laws of the United States.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency use
    text: COMMUNICATION OCCURRING THROUGH THE PLATFORM OR ENABLED BY THE PLATFORM SHOULD NOT BE USED FOR EMERGENCIES
  - summary: Restricted substance use disorder records
    text: Submit, provide, upload, or transmit any Restricted Data (as defined below) to or in connection with the Platform.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Spruce reserves the right, in its sole discretion, to determine eligibility for free trials.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Spruce Health
provenance_date: '2026-11-10'
provider_name: Spruce Health
provider_slug: spruce-health
slug: spruce-health-eligibility
source_date: '2026-11-10'
source_filename: spruce-health-eligibility.yml
source_heading: Eligibility
source_page: https://sprucehealth.com/terms-organizations/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spruce Health\naid: spruce-health\nurl: https://sprucehealth.com/terms-organizations/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You understand that the Platform is intended for use only by entities that are subject exclusively to the\n    laws of the United States.\nentity_types: []\nrestricted_uses:\n- summary: No emergency use\n  text: COMMUNICATION OCCURRING THROUGH THE PLATFORM OR ENABLED BY THE PLATFORM SHOULD NOT BE USED FOR EMERGENCIES\n- summary: Restricted substance use disorder records\n  text: Submit, provide, upload, or transmit any Restricted\
  \ Data (as defined below) to or in connection with the\n    Platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Spruce reserves the right, in its sole discretion, to determine eligibility for free trials.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spruce-health/eligibility/spruce-health-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Spruce Health's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- HIPAA
- Communications
- Secure Messaging
- Telehealth
- Patient Engagement
- Contacts
- Conversations
- Messaging
- SMS
- Voice
- VoIP
- Fax
- Video
- Webhook
- Scheduling
- Transcription
- EHR Integration
- Compliance
---
