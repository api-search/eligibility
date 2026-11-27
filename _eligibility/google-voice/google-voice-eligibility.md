---
api_specs:
- filename: google-voice-locations-api-openapi.yml
  format: yaml
  label: Google Voice Locations API
  slug: google-voice-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-voice/openapi/google-voice-locations-api-openapi.yml
- filename: google-voice-users-api-openapi.yml
  format: yaml
  label: Google Voice Users API
  slug: google-voice-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-voice/openapi/google-voice-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: But not all services mentioned may be available in your country.
  entity_types:
  - text: 'To use our services on behalf of an organization: an authorized representative of that organization must agree to these terms'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and sanctions
    text: comply with applicable laws, including export control, sanctions, and human trafficking laws
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
name: Google Voice
provenance_date: '2026-11-09'
provider_name: Google Voice
provider_slug: google-voice
slug: google-voice-eligibility
source_date: '2026-11-09'
source_filename: google-voice-eligibility.yml
source_heading: Eligibility
source_page: https://policies.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Voice\naid: google-voice\nurl: https://policies.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: But not all services mentioned may be available in your country.\nentity_types:\n- type: business\n  text: 'To use our services on behalf of an organization: an authorized representative of that organization must\n    agree to these terms'\nrestricted_uses:\n- summary: Export control and sanctions\n  text: comply with applicable laws, including export control, sanctions, and human trafficking laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-voice/eligibility/google-voice-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Google Voice's own page on 2026-11-09.
synthetic: false
tags:
- Google Voice
- Messaging
- Phone
- Telecommunications
- Voice
- Voicemail
- VoIP
---
