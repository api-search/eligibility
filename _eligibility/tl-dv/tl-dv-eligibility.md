---
api_specs:
- filename: tl-dv-meetings-api-openapi.yml
  format: yaml
  label: tl;dv Meetings API
  slug: tl-dv-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tl-dv/openapi/tl-dv-meetings-api-openapi.yml
- filename: tl-dv-notes-api-openapi.yml
  format: yaml
  label: tl;dv Notes API
  slug: tl-dv-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tl-dv/openapi/tl-dv-notes-api-openapi.yml
- filename: tl-dv-system-api-openapi.yml
  format: yaml
  label: tl;dv System API
  slug: tl-dv-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tl-dv/openapi/tl-dv-system-api-openapi.yml
- filename: tl-dv-transcripts-api-openapi.yml
  format: yaml
  label: tl;dv Transcripts API
  slug: tl-dv-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tl-dv/openapi/tl-dv-transcripts-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You will only use the Services for your own personal or business use and only in a manner that complies with all laws that apply to you.
    type: individual
  - text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that you are authorized to agree to these Terms on that organization or entity’s behalf
    type: business
  minimum_age:
    text: tldx is only for people 16 years old and over.
    value: '16'
  restricted_uses:
  - summary: Single-user account design
    text: The account’s recording allowances, concurrent session limits, and AI features are meant for the meeting activity of one person.
  - summary: Competitive use
    text: Uses the Services as a direct competitor of tldx or for the purpose of monitoring the Services’ availability, performance, functionality or for any other benchmarking or competitive purposes;
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
name: tl;dv
provenance_date: '2026-11-10'
provider_name: tl;dv
provider_slug: tl-dv
slug: tl-dv-eligibility
source_date: '2026-11-10'
source_filename: tl-dv-eligibility.yml
source_heading: Eligibility
source_page: https://tldv.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tl;dv\naid: tl-dv\nurl: https://tldv.io/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You will only use the Services for your own personal or business use and only in a manner that complies\n    with all laws that apply to you.\n- type: business\n  text: If you’re agreeing to these Terms on behalf of an organization or entity, you represent and warrant that\n    you are authorized to agree to these Terms on that organization or entity’s behalf\nrestricted_uses:\n- summary: Single-user account design\n  text: The account’s\
  \ recording allowances, concurrent session limits, and AI features are meant for the meeting\n    activity of one person.\n- summary: Competitive use\n  text: Uses the Services as a direct competitor of tldx or for the purpose of monitoring the Services’ availability,\n    performance, functionality or for any other benchmarking or competitive purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: tldx is only for people 16 years old and over.\n"
source_yaml_url: https://artifacts.apis.io/tl-dv/eligibility/tl-dv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from tl;dv's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Meetings
- Transcription
- Note Taking
- Conversation Intelligence
- Productivity
- Video
- Webhook
---
