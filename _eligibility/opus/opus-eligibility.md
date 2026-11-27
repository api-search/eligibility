---
api_specs:
- filename: opus-brand-templates-api-openapi.yml
  format: yaml
  label: Opus Brand Templates API
  slug: opus-brand-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-brand-templates-api-openapi.yml
- filename: opus-censor-jobs-api-openapi.yml
  format: yaml
  label: Opus Censor Jobs API
  slug: opus-censor-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-censor-jobs-api-openapi.yml
- filename: opus-clip-project-api-openapi.yml
  format: yaml
  label: Opus Clip Project API
  slug: opus-clip-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-clip-project-api-openapi.yml
- filename: opus-collection-api-openapi.yml
  format: yaml
  label: Opus Collection API
  slug: opus-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-collection-api-openapi.yml
- filename: opus-collection-content-api-openapi.yml
  format: yaml
  label: Opus Collection Content API
  slug: opus-collection-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-collection-content-api-openapi.yml
- filename: opus-exportableclip-api-openapi.yml
  format: yaml
  label: Opus ExportableClip API
  slug: opus-exportableclip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-exportableclip-api-openapi.yml
- filename: opus-generative-jobs-api-openapi.yml
  format: yaml
  label: Opus Generative Jobs API
  slug: opus-generative-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-generative-jobs-api-openapi.yml
- filename: opus-social-posting-api-openapi.yml
  format: yaml
  label: Opus Social Posting API
  slug: opus-social-posting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-social-posting-api-openapi.yml
- filename: opus-transcripts-api-openapi.yml
  format: yaml
  label: Opus Transcripts API
  slug: opus-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opus/openapi/opus-transcripts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: If you are using the Services on behalf of a company or organization, you represent that you have authority to act on behalf of that entity, and that such entity accepts this Agreement.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Services; however, children of all ages may use the Services if enabled by a parent or legal guardian.
    value: '16'
  restricted_uses:
  - summary: Violating laws or infringing rights
    text: Violates any law or regulation, including, without limitation, any applicable export control laws, privacy laws
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
name: Opus
provenance_date: '2026-11-10'
provider_name: Opus
provider_slug: opus
slug: opus-eligibility
source_date: '2026-11-10'
source_filename: opus-eligibility.yml
source_heading: Eligibility
source_page: https://www.opus.pro/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opus\naid: opus\nurl: https://www.opus.pro/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or\n    that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a company or organization, you represent that you have authority\n    to act on behalf of that entity, and that such entity accepts this Agreement.\nrestricted_uses:\n- summary: Violating\
  \ laws or infringing rights\n  text: Violates any law or regulation, including, without limitation, any applicable export control laws, privacy\n    laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Services; however, children of all ages may use the Services\n    if enabled by a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/opus/eligibility/opus-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Opus's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Frontier Tech
- Video
- Artificial Intelligence
- Video Editing
- Short-Form Video
- Content Creation
- Social Media
- Media
- Agents
---
