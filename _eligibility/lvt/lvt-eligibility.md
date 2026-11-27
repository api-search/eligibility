---
api_specs:
- filename: lvt-cameras-api-openapi.yml
  format: yaml
  label: LVT Cameras API
  slug: lvt-cameras-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-cameras-api-openapi.yml
- filename: lvt-events-api-openapi.yml
  format: yaml
  label: LVT Events API
  slug: lvt-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-events-api-openapi.yml
- filename: lvt-liveunits-api-openapi.yml
  format: yaml
  label: LVT Live Units API
  slug: lvt-liveunits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-liveunits-api-openapi.yml
- filename: lvt-locations-api-openapi.yml
  format: yaml
  label: LVT Locations API
  slug: lvt-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-locations-api-openapi.yml
- filename: lvt-media-api-openapi.yml
  format: yaml
  label: LVT Media API
  slug: lvt-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-media-api-openapi.yml
- filename: lvt-streams-api-openapi.yml
  format: yaml
  label: LVT Streams API
  slug: lvt-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-streams-api-openapi.yml
- filename: lvt-talkdown-api-openapi.yml
  format: yaml
  label: LVT Talkdown API
  slug: lvt-talkdown-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-talkdown-api-openapi.yml
- filename: lvt-webhooks-api-openapi.yml
  format: yaml
  label: LVT Webhooks API
  slug: lvt-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-webhooks-api-openapi.yml
- filename: lvt-public-keys-api-openapi.yml
  format: yaml
  label: LVT Public Keys API
  slug: lvt-public-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lvt/openapi/lvt-public-keys-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'YOU: (a) AGREE TO THIS AGREEMENT ON BEHALF OF THE ORGANIZATION, COMPANY, OR OTHER LEGAL ENTITY FOR WHICH YOU ACT'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or harmful Results
    text: use the System to generate or disseminate Results that are unlawful, harmful, discriminatory, deceptive, defamatory, or otherwise objectionable
  - summary: Export restrictions
    text: Customer represents and warrants that the System is not being and will not be acquired for, shipped, transferred, or re-exported
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
name: LVT
provenance_date: '2026-11-10'
provider_name: LVT
provider_slug: lvt
slug: lvt-eligibility
source_date: '2026-11-10'
source_filename: lvt-eligibility.yml
source_heading: Eligibility
source_page: https://www.lvt.com/legal/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LVT\naid: lvt\nurl: https://www.lvt.com/legal/msa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'YOU: (a) AGREE TO THIS AGREEMENT ON BEHALF OF THE ORGANIZATION, COMPANY, OR OTHER LEGAL ENTITY FOR WHICH\n    YOU ACT'\nrestricted_uses:\n- summary: Unlawful or harmful Results\n  text: use the System to generate or disseminate Results that are unlawful, harmful, discriminatory, deceptive,\n    defamatory, or otherwise objectionable\n- summary: Export restrictions\n  text: Customer represents and warrants that the System\
  \ is not being and will not be acquired for, shipped, transferred,\n    or re-exported\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lvt/eligibility/lvt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from LVT's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Physical Security
- Video Surveillance
- Camera
- Video Streaming
- WebRTC
- RTSP
- ONVIF
- IoT
- Alerts
- Webhook
- Public Safety
- Retail
- Critical Infrastructure
---
