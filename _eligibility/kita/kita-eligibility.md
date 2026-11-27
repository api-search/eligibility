---
api_specs:
- filename: kita-applications-api-openapi.yml
  format: yaml
  label: Kita Applications API
  slug: kita-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-applications-api-openapi.yml
- filename: kita-batch-api-openapi.yml
  format: yaml
  label: Kita Batch API
  slug: kita-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-batch-api-openapi.yml
- filename: kita-conversation-api-openapi.yml
  format: yaml
  label: Kita Conversation API
  slug: kita-conversation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-conversation-api-openapi.yml
- filename: kita-credit-api-openapi.yml
  format: yaml
  label: Kita Credit API
  slug: kita-credit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-credit-api-openapi.yml
- filename: kita-documents-api-openapi.yml
  format: yaml
  label: Kita Documents API
  slug: kita-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-documents-api-openapi.yml
- filename: kita-exports-api-openapi.yml
  format: yaml
  label: Kita Exports API
  slug: kita-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-exports-api-openapi.yml
- filename: kita-folders-api-openapi.yml
  format: yaml
  label: Kita Folders API
  slug: kita-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-folders-api-openapi.yml
- filename: kita-memo-api-openapi.yml
  format: yaml
  label: Kita Memo API
  slug: kita-memo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-memo-api-openapi.yml
- filename: kita-processing-api-openapi.yml
  format: yaml
  label: Kita Processing API
  slug: kita-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-processing-api-openapi.yml
- filename: kita-results-api-openapi.yml
  format: yaml
  label: Kita Results API
  slug: kita-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-results-api-openapi.yml
- filename: kita-schemas-api-openapi.yml
  format: yaml
  label: Kita Schemas API
  slug: kita-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-schemas-api-openapi.yml
- filename: kita-transcripts-api-openapi.yml
  format: yaml
  label: Kita Transcripts API
  slug: kita-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-transcripts-api-openapi.yml
- filename: kita-verification-api-openapi.yml
  format: yaml
  label: Kita Verification API
  slug: kita-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-verification-api-openapi.yml
- filename: kita-webhooks-api-openapi.yml
  format: yaml
  label: Kita Webhooks API
  slug: kita-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kita/openapi/kita-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Services are provided for use by persons located in the United States. We make no claims that the Services are accessible or appropriate outside the United States.
  entity_types:
  - text: If you are using the Services as an individual, you represent and warrant that you are of legal age to form a binding contract.
    type: individual
  - text: If you are using the Services on behalf of an entity, you represent and warrant that you have authority to bind that entity
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract.
    value: legal age
  restricted_uses:
  - summary: Sensitive personal information
    text: You agree not to collect, process, or store Sensitive Personal Information using the Services
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
name: Kita
provenance_date: '2026-11-09'
provider_name: Kita
provider_slug: kita
slug: kita-eligibility
source_date: '2026-11-09'
source_filename: kita-eligibility.yml
source_heading: Eligibility
source_page: https://www.kita.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kita\naid: kita\nurl: https://www.kita.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Services are provided for use by persons located in the United States. We make no claims that the Services\n    are accessible or appropriate outside the United States.\nentity_types:\n- type: individual\n  text: If you are using the Services as an individual, you represent and warrant that you are of legal age to form\n    a binding contract.\n- type: business\n  text: If you are using the Services on behalf of an entity, you represent and warrant that you have authority\n  \
  \  to bind that entity\nrestricted_uses:\n- summary: Sensitive personal information\n  text: You agree not to collect, process, or store Sensitive Personal Information using the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you are of legal age to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/kita/eligibility/kita-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Kita's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Underwriting
- Credit Scoring
- Document Intelligence
- Document Extraction
- Fraud Prevention
- Artificial Intelligence
- Computer Vision
- Emerging Markets
- Loan Origination
---
