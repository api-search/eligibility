---
api_specs:
- filename: atlas-cloud-balance-api-openapi.yml
  format: yaml
  label: Atlas Cloud Balance API
  slug: atlas-cloud-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-balance-api-openapi.yml
- filename: atlas-cloud-completions-api-openapi.yml
  format: yaml
  label: Atlas Cloud Completions API
  slug: atlas-cloud-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-completions-api-openapi.yml
- filename: atlas-cloud-images-api-openapi.yml
  format: yaml
  label: Atlas Cloud Images API
  slug: atlas-cloud-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-images-api-openapi.yml
- filename: atlas-cloud-messages-api-openapi.yml
  format: yaml
  label: Atlas Cloud Messages API
  slug: atlas-cloud-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-messages-api-openapi.yml
- filename: atlas-cloud-model-api-openapi.yml
  format: yaml
  label: Atlas Cloud Model API
  slug: atlas-cloud-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-model-api-openapi.yml
- filename: atlas-cloud-model-costs-api-openapi.yml
  format: yaml
  label: Atlas Cloud Model Costs API
  slug: atlas-cloud-model-costs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-model-costs-api-openapi.yml
- filename: atlas-cloud-model-usage-api-openapi.yml
  format: yaml
  label: Atlas Cloud Model Usage API
  slug: atlas-cloud-model-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-model-usage-api-openapi.yml
- filename: atlas-cloud-v1beta-api-openapi.yml
  format: yaml
  label: Atlas Cloud V1Beta API
  slug: atlas-cloud-v1beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-v1beta-api-openapi.yml
- filename: atlas-cloud-webhooks-api-openapi.yml
  format: yaml
  label: Atlas Cloud Webhooks API
  slug: atlas-cloud-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-webhooks-api-openapi.yml
- filename: atlas-cloud-chat-completions-api-openapi.yml
  format: yaml
  label: Atlas Cloud Chat Completions API
  slug: atlas-cloud-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atlas-cloud/openapi/atlas-cloud-chat-completions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: whether personally or on behalf of an entity ("you")
    type: business
  minimum_age:
    text: you are not a minor in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Industry-specific regulated data
    text: The Services are not tailored to comply with industry-specific regulations (HIPAA, FISMA, etc.), so if your interactions would be subjected to such laws, you may not use the Services.
  - summary: Life-critical or harmful applications
    text: you will not use the Services in any application where a failure, delay, or inaccurate output could reasonably be expected to result in death, personal injury, or severe physical, financial, or environmental harm.
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
name: Atlas Cloud
provenance_date: '2026-11-09'
provider_name: Atlas Cloud
provider_slug: atlas-cloud
slug: atlas-cloud-eligibility
source_date: '2026-11-09'
source_filename: atlas-cloud-eligibility.yml
source_heading: Eligibility
source_page: https://www.atlascloud.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlas Cloud\naid: atlas-cloud\nurl: https://www.atlascloud.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (\"you\")\nrestricted_uses:\n- summary: Industry-specific regulated data\n  text: The Services are not tailored to comply with industry-specific regulations (HIPAA,\
  \ FISMA, etc.), so if your\n    interactions would be subjected to such laws, you may not use the Services.\n- summary: Life-critical or harmful applications\n  text: you will not use the Services in any application where a failure, delay, or inaccurate output could reasonably\n    be expected to result in death, personal injury, or severe physical, financial, or environmental harm.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are not a minor in the jurisdiction in which you reside\n"
source_yaml_url: https://artifacts.apis.io/atlas-cloud/eligibility/atlas-cloud-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Atlas Cloud's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Model Routing
- Image Generation
- Video Generation
- Inference
- GPU Cloud
- MCP
---
