---
api_specs:
- filename: reactor-helios-asyncapi.yml
  format: yaml
  label: Reactor Realtime Video API
  slug: reactor-realtime-video-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/reactor/asyncapi/reactor-helios-asyncapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users may not be on the List of Specially Designated Nationals or located in sanctioned countries or territories (Section 16).
  entity_types:
  - text: To use the Service, you must be at least 13 years old.
    type: individual
  - text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual's employer (such entity, an "Organization").
    type: business
  minimum_age:
    text: To use the Service, you must be at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You will comply with all applicable import and export and re-export control and trade and economic sanctions laws and regulations
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
name: Reactor
provenance_date: '2026-11-10'
provider_name: Reactor
provider_slug: reactor
slug: reactor-eligibility
source_date: '2026-11-10'
source_filename: reactor-eligibility.yml
source_heading: Eligibility
source_page: https://www.reactor.inc/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reactor\naid: reactor\nurl: https://www.reactor.inc/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users may not be on the List of Specially Designated Nationals or located in sanctioned countries or territories\n    (Section 16).\nentity_types:\n- type: individual\n  text: To use the Service, you must be at least 13 years old.\n- type: business\n  text: An individual may access and/or use the Service on behalf of a company or other entity, such as that individual's\n    employer (such entity, an \"Organization\").\nrestricted_uses:\n- summary: Export and sanctions restrictions\n\
  \  text: You will comply with all applicable import and export and re-export control and trade and economic sanctions\n    laws and regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: To use the Service, you must be at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/reactor/eligibility/reactor-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Reactor's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Generative AI
- Real-Time
- WebRTC
- Streaming
- SDK
- Media
---
