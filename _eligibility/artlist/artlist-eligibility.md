---
api_specs:
- filename: artlist-album-api-openapi.yml
  format: yaml
  label: Artlist Album API
  slug: artlist-album-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artlist/openapi/artlist-album-api-openapi.yml
- filename: artlist-artist-api-openapi.yml
  format: yaml
  label: Artlist Artist API
  slug: artlist-artist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artlist/openapi/artlist-artist-api-openapi.yml
- filename: artlist-downloadable-api-openapi.yml
  format: yaml
  label: Artlist Downloadable API
  slug: artlist-downloadable-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artlist/openapi/artlist-downloadable-api-openapi.yml
- filename: artlist-song-api-openapi.yml
  format: yaml
  label: Artlist Song API
  slug: artlist-song-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/artlist/openapi/artlist-song-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company is committed to complying with the sanctions laws and regulations of the United States, the EU and Israel. Accordingly, we will not trade with or provide any services to sanctioned countries or individuals/entities named on a sanctions list. The Voice Cloning Feature is not available to residents of the State of Illinois, the United States.
  entity_types:
  - text: Each entity or person purchasing a Team subscription (“Team Account”) shall select a person to register the Team Account (“Admin”) which shall act as its authorized representative
    type: business
  minimum_age:
    text: your age does not limit or restrict you, under applicable law or jurisdiction, from lawfully entering into this Agreement
    value: null
  restricted_uses:
  - summary: Voice cloning biometric identification
    text: You represent and warrant that you will not use, or permit anyone else to use, the Voice Cloning Feature for the purpose of biometric identification
  - summary: AI training prohibited
    text: You are forbidden from using any Proprietary Content and/or data and/or information and/or the Site for purposes of machine learning and/or Artificial Intelligence (“AI”) training.
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
name: Artlist
provenance_date: '2026-11-09'
provider_name: Artlist
provider_slug: artlist
slug: artlist-eligibility
source_date: '2026-11-09'
source_filename: artlist-eligibility.yml
source_heading: Eligibility
source_page: https://artlist.io/help-center/privacy-terms/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Artlist\naid: artlist\nurl: https://artlist.io/help-center/privacy-terms/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company is committed to complying with the sanctions laws and regulations of the United States, the\n    EU and Israel. Accordingly, we will not trade with or provide any services to sanctioned countries or individuals/entities\n    named on a sanctions list. The Voice Cloning Feature is not available to residents of the State of Illinois,\n    the United States.\nentity_types:\n- type: business\n  text: Each entity or person purchasing a Team\
  \ subscription (“Team Account”) shall select a person to register\n    the Team Account (“Admin”) which shall act as its authorized representative\nrestricted_uses:\n- summary: Voice cloning biometric identification\n  text: You represent and warrant that you will not use, or permit anyone else to use, the Voice Cloning Feature\n    for the purpose of biometric identification\n- summary: AI training prohibited\n  text: You are forbidden from using any Proprietary Content and/or data and/or information and/or the Site for\n    purposes of machine learning and/or Artificial Intelligence (“AI”) training.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: your age does not limit or restrict you, under applicable law or jurisdiction, from lawfully entering into\n    this Agreement\n"
source_yaml_url: https://artifacts.apis.io/artlist/eligibility/artlist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Artlist's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Audio
- Media
- Stock Media
- Content Licensing
- Creative Tools
- Search
- Generative AI
- Video
---
