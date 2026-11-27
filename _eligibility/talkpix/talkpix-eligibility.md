---
api_specs:
- filename: talkpix-estimate-api-openapi.yml
  format: yaml
  label: TalkPix API Estimate API
  slug: talkpix-estimate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-estimate-api-openapi.yml
- filename: talkpix-me-api-openapi.yml
  format: yaml
  label: TalkPix API Me API
  slug: talkpix-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-me-api-openapi.yml
- filename: talkpix-talkpix-api-api-api-openapi.yml
  format: yaml
  label: TalkPix API TalkPix API API
  slug: talkpix-talkpix-api-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-talkpix-api-api-api-openapi.yml
- filename: talkpix-uploads-api-openapi.yml
  format: yaml
  label: TalkPix API Uploads API
  slug: talkpix-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-uploads-api-openapi.yml
- filename: talkpix-videos-api-openapi.yml
  format: yaml
  label: TalkPix API Videos API
  slug: talkpix-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-videos-api-openapi.yml
- filename: talkpix-voices-api-openapi.yml
  format: yaml
  label: TalkPix API Voices API
  slug: talkpix-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/talkpix/openapi/talkpix-voices-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: TalkPix is for adults only.
    type: individual
  - text: Developer API. API access is part of the Service.
    type: developer
  minimum_age:
    text: You must be at least 18 years old to use it
    value: '18'
  restricted_uses:
  - summary: Real persons without consent
    text: Depict public figures, politicians, or any real person without the rights and consent required for that use.
  - summary: Political or electoral content
    text: Produce political, electoral, or campaign content, or content that could influence an election.
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
name: TalkPix API
provenance_date: '2026-11-10'
provider_name: TalkPix API
provider_slug: talkpix
slug: talkpix-eligibility
source_date: '2026-11-10'
source_filename: talkpix-eligibility.yml
source_heading: Eligibility
source_page: https://www.talkpix.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TalkPix API\naid: talkpix\nurl: https://www.talkpix.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: TalkPix is for adults only.\n- type: developer\n  text: Developer API. API access is part of the Service.\nrestricted_uses:\n- summary: Real persons without consent\n  text: Depict public figures, politicians, or any real person without the rights and consent required for that\n    use.\n- summary: Political or electoral content\n  text: Produce political, electoral, or campaign content, or content that could influence an election.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use it\n"
source_yaml_url: https://artifacts.apis.io/talkpix/eligibility/talkpix-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from TalkPix API's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Talking Photo
- Media
---
