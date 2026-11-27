---
api_specs:
- filename: layercall-com-ai-agents-api-openapi.yml
  format: yaml
  label: layercall-com AI agents API
  slug: layercall-com-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-ai-agents-api-openapi.yml
- filename: layercall-com-batch-api-openapi.yml
  format: yaml
  label: layercall-com Batch API
  slug: layercall-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-batch-api-openapi.yml
- filename: layercall-com-device-api-openapi.yml
  format: yaml
  label: layercall-com Device API
  slug: layercall-com-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-device-api-openapi.yml
- filename: layercall-com-reputation-api-openapi.yml
  format: yaml
  label: layercall-com Reputation API
  slug: layercall-com-reputation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-reputation-api-openapi.yml
- filename: layercall-com-rules-api-openapi.yml
  format: yaml
  label: layercall-com Rules API
  slug: layercall-com-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-rules-api-openapi.yml
- filename: layercall-com-scoring-api-openapi.yml
  format: yaml
  label: layercall-com Scoring API
  slug: layercall-com-scoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-scoring-api-openapi.yml
- filename: layercall-com-unified-api-openapi.yml
  format: yaml
  label: layercall-com Unified API
  slug: layercall-com-unified-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/layercall-com/openapi/layercall-com-unified-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you are authorized to accept these Terms for it.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unlawful discrimination or sole automated decisions
    text: Use results to unlawfully discriminate against individuals, or as the sole automated basis for decisions that produce legal or similarly significant effects on a person without human review, where such review is required by law.
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
name: layercall-com
provenance_date: '2026-11-09'
provider_name: layercall-com
provider_slug: layercall-com
slug: layercall-com-eligibility
source_date: '2026-11-09'
source_filename: layercall-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.layercall.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: layercall-com\naid: layercall-com\nurl: https://www.layercall.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you are authorized to accept\n    these Terms for it.\nrestricted_uses:\n- summary: Unlawful discrimination or sole automated decisions\n  text: Use results to unlawfully discriminate against individuals, or as the sole automated basis for decisions\n    that produce legal or similarly significant effects on a person without human review,\
  \ where such review is required\n    by law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/layercall-com/eligibility/layercall-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from layercall-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fraud Prevention
- TrustIntelligence
- Security
---
