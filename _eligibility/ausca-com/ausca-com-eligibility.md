---
api_specs:
- filename: ausca-com-agent-inboxes-api-openapi.yml
  format: yaml
  label: Ausca Agent Inboxes API
  slug: ausca-com-agent-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-agent-inboxes-api-openapi.yml
- filename: ausca-com-analyze-document-api-openapi.yml
  format: yaml
  label: Ausca Analyze Document API
  slug: ausca-com-analyze-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-analyze-document-api-openapi.yml
- filename: ausca-com-artifacts-api-openapi.yml
  format: yaml
  label: Ausca Artifacts API
  slug: ausca-com-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-artifacts-api-openapi.yml
- filename: ausca-com-browser-sessions-api-openapi.yml
  format: yaml
  label: Ausca Browser Sessions API
  slug: ausca-com-browser-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-browser-sessions-api-openapi.yml
- filename: ausca-com-extend-inbox-api-openapi.yml
  format: yaml
  label: Ausca Extend Inbox API
  slug: ausca-com-extend-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-extend-inbox-api-openapi.yml
- filename: ausca-com-extract-text-api-openapi.yml
  format: yaml
  label: Ausca Extract Text API
  slug: ausca-com-extract-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-extract-text-api-openapi.yml
- filename: ausca-com-invocations-api-openapi.yml
  format: yaml
  label: Ausca Invocations API
  slug: ausca-com-invocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-invocations-api-openapi.yml
- filename: ausca-com-lease-browser-api-openapi.yml
  format: yaml
  label: Ausca Lease Browser API
  slug: ausca-com-lease-browser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-lease-browser-api-openapi.yml
- filename: ausca-com-offers-api-openapi.yml
  format: yaml
  label: Ausca Offers API
  slug: ausca-com-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-offers-api-openapi.yml
- filename: ausca-com-open-inbox-api-openapi.yml
  format: yaml
  label: Ausca Open Inbox API
  slug: ausca-com-open-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-open-inbox-api-openapi.yml
- filename: ausca-com-transcribe-media-api-openapi.yml
  format: yaml
  label: Ausca Transcribe Media API
  slug: ausca-com-transcribe-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-transcribe-media-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Service discovery and an unsigned payment challenge do not buy or start a job.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ausca
provenance_date: '2026-11-09'
provider_name: Ausca
provider_slug: ausca-com
slug: ausca-com-eligibility
source_date: '2026-11-09'
source_filename: ausca-com-eligibility.yml
source_heading: Eligibility
source_page: https://ausca.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ausca\naid: ausca-com\nurl: https://ausca.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Service discovery and an unsigned payment challenge do not buy or start a job.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ausca-com/eligibility/ausca-com-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Ausca's own page on 2026-11-09.
synthetic: false
tags:
- Pay-per-call APIs
- Agent Infrastructure
- Document OCR
- Media transcription
- Inbox verification
---
