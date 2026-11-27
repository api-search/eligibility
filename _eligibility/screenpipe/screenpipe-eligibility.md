---
api_specs:
- filename: screenpipe-activity-api-openapi.yml
  format: yaml
  label: Screenpipe Activity API
  slug: screenpipe-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-activity-api-openapi.yml
- filename: screenpipe-audio-api-openapi.yml
  format: yaml
  label: Screenpipe Audio API
  slug: screenpipe-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-audio-api-openapi.yml
- filename: screenpipe-cloud-archive-api-openapi.yml
  format: yaml
  label: Screenpipe Cloud Archive API
  slug: screenpipe-cloud-archive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-cloud-archive-api-openapi.yml
- filename: screenpipe-cloud-sync-api-openapi.yml
  format: yaml
  label: Screenpipe Cloud Sync API
  slug: screenpipe-cloud-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-cloud-sync-api-openapi.yml
- filename: screenpipe-data-management-api-openapi.yml
  format: yaml
  label: Screenpipe Data Management API
  slug: screenpipe-data-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-data-management-api-openapi.yml
- filename: screenpipe-data-retention-api-openapi.yml
  format: yaml
  label: Screenpipe Data Retention API
  slug: screenpipe-data-retention-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-data-retention-api-openapi.yml
- filename: screenpipe-database-api-openapi.yml
  format: yaml
  label: Screenpipe Database API
  slug: screenpipe-database-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-database-api-openapi.yml
- filename: screenpipe-elements-api-openapi.yml
  format: yaml
  label: Screenpipe Elements API
  slug: screenpipe-elements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-elements-api-openapi.yml
- filename: screenpipe-experimental-api-openapi.yml
  format: yaml
  label: Screenpipe Experimental API
  slug: screenpipe-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-experimental-api-openapi.yml
- filename: screenpipe-frames-api-openapi.yml
  format: yaml
  label: Screenpipe Frames API
  slug: screenpipe-frames-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-frames-api-openapi.yml
- filename: screenpipe-meetings-api-openapi.yml
  format: yaml
  label: Screenpipe Meetings API
  slug: screenpipe-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-meetings-api-openapi.yml
- filename: screenpipe-memories-api-openapi.yml
  format: yaml
  label: Screenpipe Memories API
  slug: screenpipe-memories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-memories-api-openapi.yml
- filename: screenpipe-search-api-openapi.yml
  format: yaml
  label: Screenpipe Search API
  slug: screenpipe-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-search-api-openapi.yml
- filename: screenpipe-speakers-api-openapi.yml
  format: yaml
  label: Screenpipe Speakers API
  slug: screenpipe-speakers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-speakers-api-openapi.yml
- filename: screenpipe-system-api-openapi.yml
  format: yaml
  label: Screenpipe System API
  slug: screenpipe-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-system-api-openapi.yml
- filename: screenpipe-tags-api-openapi.yml
  format: yaml
  label: Screenpipe Tags API
  slug: screenpipe-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-tags-api-openapi.yml
- filename: screenpipe-vault-api-openapi.yml
  format: yaml
  label: Screenpipe Vault API
  slug: screenpipe-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-vault-api-openapi.yml
- filename: screenpipe-vision-api-openapi.yml
  format: yaml
  label: Screenpipe Vision API
  slug: screenpipe-vision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/screenpipe/openapi/screenpipe-vision-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal
  entity_types:
  - text: If you use our Services on behalf of another person or entity, (a) all references to “you” throughout these Terms will include that person or entity
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: Decisions with legal effects
    text: use Output as the sole basis for making decisions that have legal or similarly significant effects on an individual, including decisions relating to employment, housing, credit, insurance, education, criminal justice, or health care
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
name: Screenpipe
provenance_date: '2026-11-10'
provider_name: Screenpipe
provider_slug: screenpipe
slug: screenpipe-eligibility
source_date: '2026-11-10'
source_filename: screenpipe-eligibility.yml
source_heading: Eligibility
source_page: https://screenpipe.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Screenpipe\naid: screenpipe\nurl: https://screenpipe.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are located in, or a citizen or resident of any state, country, territory\n    or other jurisdiction that is embargoed by the United States or where your use of the Services would be illegal\nentity_types:\n- type: business\n  text: If you use our Services on behalf of another person or entity, (a) all references to “you” throughout these\n    Terms will include that person or entity\nrestricted_uses:\n- summary: Decisions\
  \ with legal effects\n  text: use Output as the sole basis for making decisions that have legal or similarly significant effects on an\n    individual, including decisions relating to employment, housing, credit, insurance, education, criminal justice,\n    or health care\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/screenpipe/eligibility/screenpipe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Screenpipe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Screen Recording
- Screen Memory
- Audio Transcription
- Meeting Intelligence
- Local-First
- Privacy
- AI Agents
- MCP
- Developer Tools
- Productivity
---
