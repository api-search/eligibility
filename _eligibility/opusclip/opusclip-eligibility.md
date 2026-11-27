---
api_specs:
- filename: opusclip-brand-templates-api-openapi.yml
  format: yaml
  label: OpusClip Brand Templates API
  slug: opusclip-brand-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-brand-templates-api-openapi.yml
- filename: opusclip-censor-jobs-api-openapi.yml
  format: yaml
  label: OpusClip Censor Jobs API
  slug: opusclip-censor-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-censor-jobs-api-openapi.yml
- filename: opusclip-clip-project-api-openapi.yml
  format: yaml
  label: OpusClip Clip Project API
  slug: opusclip-clip-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-clip-project-api-openapi.yml
- filename: opusclip-collection-api-openapi.yml
  format: yaml
  label: OpusClip Collection API
  slug: opusclip-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-collection-api-openapi.yml
- filename: opusclip-collection-content-api-openapi.yml
  format: yaml
  label: OpusClip Collection Content API
  slug: opusclip-collection-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-collection-content-api-openapi.yml
- filename: opusclip-exportableclip-api-openapi.yml
  format: yaml
  label: OpusClip ExportableClip API
  slug: opusclip-exportableclip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-exportableclip-api-openapi.yml
- filename: opusclip-generative-jobs-api-openapi.yml
  format: yaml
  label: OpusClip Generative Jobs API
  slug: opusclip-generative-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-generative-jobs-api-openapi.yml
- filename: opusclip-social-posting-api-openapi.yml
  format: yaml
  label: OpusClip Social Posting API
  slug: opusclip-social-posting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-social-posting-api-openapi.yml
- filename: opusclip-transcripts-api-openapi.yml
  format: yaml
  label: OpusClip Transcripts API
  slug: opusclip-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opusclip/openapi/opusclip-transcripts-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: You must be at least 16 years old to use the Services; however, children of all ages may use the Services if enabled by a parent or legal guardian.
    type: individual
  - text: If you are using the Services on behalf of a company or organization, you represent that you have authority to act on behalf of that entity, and that such entity accepts this Agreement.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Services; however, children of all ages may use the Services if enabled by a parent or legal guardian.
    value: '16'
  restricted_uses:
  - summary: Infringing or harmful use
    text: Infringes or violates the intellectual property rights or any other rights of anyone else (including OpusClip).
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
name: OpusClip
provenance_date: '2026-11-10'
provider_name: OpusClip
provider_slug: opusclip
slug: opusclip-eligibility
source_date: '2026-11-10'
source_filename: opusclip-eligibility.yml
source_heading: Eligibility
source_page: https://www.opus.pro/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpusClip\naid: opusclip\nurl: https://www.opus.pro/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in a country subject to a U.S. Government embargo, or\n    that has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Services; however, children of all ages may use the Services\n    if enabled by a parent or legal guardian.\n- type: business\n  text: If you are using the Services on\
  \ behalf of a company or organization, you represent that you have authority\n    to act on behalf of that entity, and that such entity accepts this Agreement.\nrestricted_uses:\n- summary: Infringing or harmful use\n  text: Infringes or violates the intellectual property rights or any other rights of anyone else (including OpusClip).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Services; however, children of all ages may use the Services\n    if enabled by a parent or legal guardian.\n"
source_yaml_url: https://artifacts.apis.io/opusclip/eligibility/opusclip-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from OpusClip's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Video
- Artificial Intelligence
- Video Editing
- Short-Form Video
- Social Media
- Content Creation
- MCP
- Developer API
---
