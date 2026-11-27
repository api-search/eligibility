---
api_specs:
- filename: zeroentropy-admin-api-openapi.yml
  format: yaml
  label: ZeroEntropy Admin API
  slug: zeroentropy-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-admin-api-openapi.yml
- filename: zeroentropy-collections-api-openapi.yml
  format: yaml
  label: ZeroEntropy Collections API
  slug: zeroentropy-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-collections-api-openapi.yml
- filename: zeroentropy-documents-api-openapi.yml
  format: yaml
  label: ZeroEntropy Documents API
  slug: zeroentropy-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-documents-api-openapi.yml
- filename: zeroentropy-models-api-openapi.yml
  format: yaml
  label: ZeroEntropy Models API
  slug: zeroentropy-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-models-api-openapi.yml
- filename: zeroentropy-queries-api-openapi.yml
  format: yaml
  label: ZeroEntropy Queries API
  slug: zeroentropy-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-queries-api-openapi.yml
- filename: zeroentropy-status-api-openapi.yml
  format: yaml
  label: ZeroEntropy Status API
  slug: zeroentropy-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-status-api-openapi.yml
- filename: zeroentropy-usage-api-openapi.yml
  format: yaml
  label: ZeroEntropy Usage API
  slug: zeroentropy-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zeroentropy/openapi/zeroentropy-usage-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If acting on behalf of an entity, you represent you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: You must be at least 18 years old to use ZeroEntropy Services.
    value: '18'
  restricted_uses:
  - summary: Fraudulent, unlawful or abusive use
    text: Use the Services for fraudulent, unlawful, abusive, offensive, or prohibited activities as defined under local law.
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
name: ZeroEntropy
provenance_date: '2026-11-10'
provider_name: ZeroEntropy
provider_slug: zeroentropy
slug: zeroentropy-eligibility
source_date: '2026-11-10'
source_filename: zeroentropy-eligibility.yml
source_heading: Eligibility
source_page: https://www.zeroentropy.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZeroEntropy\naid: zeroentropy\nurl: https://www.zeroentropy.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If acting on behalf of an entity, you represent you have authority to bind that entity to these Terms.\nrestricted_uses:\n- summary: Fraudulent, unlawful or abusive use\n  text: Use the Services for fraudulent, unlawful, abusive, offensive, or prohibited activities as defined under\n    local law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You\
  \ must be at least 18 years old to use ZeroEntropy Services.\n"
source_yaml_url: https://artifacts.apis.io/zeroentropy/eligibility/zeroentropy-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ZeroEntropy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- Artificial Intelligence
- Search
- Retrieval
- Embeddings
- Reranking
- RAG
---
