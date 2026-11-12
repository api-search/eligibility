---
api_specs:
- filename: clipugc-com-characters-api-openapi.yml
  format: yaml
  label: ClipUGC Characters API
  slug: clipugc-com-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipugc-com/openapi/clipugc-com-characters-api-openapi.yml
- filename: clipugc-com-clips-api-openapi.yml
  format: yaml
  label: ClipUGC Clips API
  slug: clipugc-com-clips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipugc-com/openapi/clipugc-com-clips-api-openapi.yml
- filename: clipugc-com-credits-api-openapi.yml
  format: yaml
  label: ClipUGC Credits API
  slug: clipugc-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipugc-com/openapi/clipugc-com-credits-api-openapi.yml
- filename: clipugc-com-finished-videos-api-openapi.yml
  format: yaml
  label: ClipUGC Finished videos API
  slug: clipugc-com-finished-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipugc-com/openapi/clipugc-com-finished-videos-api-openapi.yml
- filename: clipugc-com-hooks-api-openapi.yml
  format: yaml
  label: ClipUGC Hooks API
  slug: clipugc-com-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipugc-com/openapi/clipugc-com-hooks-api-openapi.yml
- filename: clipugc-com-looks-api-openapi.yml
  format: yaml
  label: ClipUGC Looks API
  slug: clipugc-com-looks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipugc-com/openapi/clipugc-com-looks-api-openapi.yml
- filename: clipugc-com-uploads-api-openapi.yml
  format: yaml
  label: ClipUGC Uploads API
  slug: clipugc-com-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipugc-com/openapi/clipugc-com-uploads-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Username restrictions
    text: You may not use as a username any name that is offensive, vulgar or obscene.
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
name: ClipUGC
provenance_date: '2026-11-09'
provider_name: ClipUGC
provider_slug: clipugc-com
slug: clipugc-com-eligibility
source_date: '2026-11-09'
source_filename: clipugc-com-eligibility.yml
source_heading: Eligibility
source_page: https://clipugc.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClipUGC\naid: clipugc-com\nurl: https://clipugc.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Username restrictions\n  text: You may not use as a username any name that is offensive, vulgar or obscene.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/clipugc-com/eligibility/clipugc-com-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from ClipUGC's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Video Generation
- UGC
- AI Influencers
- Mobile App Marketing
- Video
- MCP
- CLI
---
