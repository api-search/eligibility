---
api_specs:
- filename: decart-client-api-openapi.yml
  format: yaml
  label: Decart Client API
  slug: decart-client-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decart/openapi/decart-client-api-openapi.yml
- filename: decart-files-api-openapi.yml
  format: yaml
  label: Decart Files API
  slug: decart-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decart/openapi/decart-files-api-openapi.yml
- filename: decart-generate-api-openapi.yml
  format: yaml
  label: Decart Generate API
  slug: decart-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decart/openapi/decart-generate-api-openapi.yml
- filename: decart-jobs-api-openapi.yml
  format: yaml
  label: Decart Jobs API
  slug: decart-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decart/openapi/decart-jobs-api-openapi.yml
- filename: decart-models-api-openapi.yml
  format: yaml
  label: Decart Models API
  slug: decart-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decart/openapi/decart-models-api-openapi.yml
- filename: decart-realtime-api-openapi.yml
  format: yaml
  label: Decart Realtime API
  slug: decart-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/decart/openapi/decart-realtime-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform is only intended for individuals aged thirteen (13) years or older.
    type: individual
  - source: https://docs.platform.decart.ai/resources/aup
    text: This AUP applies to business, users, consumers, developers, integrators, resellers, authorities, individuals, organizations
    type: business
  minimum_age:
    text: The Platform is only intended for individuals aged thirteen (13) years or older.
    value: '13'
  restricted_uses:
  - summary: Violation of law or third-party rights
    text: use the Platform or the Content in violation of these Terms, applicable law or third-party rights.
  - source: https://docs.platform.decart.ai/resources/aup
    summary: High-risk uses prohibited absent agreement
    text: The following high-risk uses and activities are prohibited unless otherwise agreed between Decart and you, and only where you can demonstrate full compliance with applicable law
  - source: https://docs.platform.decart.ai/resources/aup
    summary: Medical, autonomous weapons, surveillance
    text: Using the Offers for medical diagnosis, treatment, autonomous weapons, surveillance
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
name: Decart
provenance_date: '2026-11-09'
provider_name: Decart
provider_slug: decart
slug: decart-eligibility
source_date: '2026-11-09'
source_filename: decart-eligibility.yml
source_heading: Eligibility
source_page: https://docs.platform.decart.ai/resources/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Decart\naid: decart\nurl: https://docs.platform.decart.ai/resources/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://docs.platform.decart.ai/resources/aup\n  - https://docs.platform.decart.ai/resources/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Platform is only intended for individuals aged thirteen (13) years or older.\n- type: business\n  text: This AUP applies to business, users, consumers, developers, integrators, resellers, authorities, individuals,\n    organizations\n  source: https://docs.platform.decart.ai/resources/aup\n\
  restricted_uses:\n- summary: Violation of law or third-party rights\n  text: use the Platform or the Content in violation of these Terms, applicable law or third-party rights.\n- summary: High-risk uses prohibited absent agreement\n  text: The following high-risk uses and activities are prohibited unless otherwise agreed between Decart and you,\n    and only where you can demonstrate full compliance with applicable law\n  source: https://docs.platform.decart.ai/resources/aup\n- summary: Medical, autonomous weapons, surveillance\n  text: Using the Offers for medical diagnosis, treatment, autonomous weapons, surveillance\n  source: https://docs.platform.decart.ai/resources/aup\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Platform is only intended for individuals aged thirteen (13) years or older.\n"
source_yaml_url: https://artifacts.apis.io/decart/eligibility/decart-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Decart's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Video
- Video Generation
- Video Editing
- Image Editing
- Real-Time
- Generative AI
- World Models
- Streaming
- WebRTC
- Media
- Developer Tools
- Company
- A2A
---
