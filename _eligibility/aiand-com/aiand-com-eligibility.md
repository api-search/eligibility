---
api_specs:
- filename: aiand-com-files-api-openapi.yml
  format: yaml
  label: ai& Files API
  slug: aiand-com-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiand-com/openapi/aiand-com-files-api-openapi.yml
- filename: aiand-com-logs-api-openapi.yml
  format: yaml
  label: ai& Logs API
  slug: aiand-com-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiand-com/openapi/aiand-com-logs-api-openapi.yml
- filename: aiand-com-openai-api-openapi.yml
  format: yaml
  label: ai& Openai API
  slug: aiand-com-openai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiand-com/openapi/aiand-com-openai-api-openapi.yml
- filename: aiand-com-uploads-api-openapi.yml
  format: yaml
  label: ai& Uploads API
  slug: aiand-com-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiand-com/openapi/aiand-com-uploads-api-openapi.yml
- filename: aiand-com-videos-api-openapi.yml
  format: yaml
  label: ai& Videos API
  slug: aiand-com-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiand-com/openapi/aiand-com-videos-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Website on behalf of a company or other entity, you represent and warrant that you have authority to bind that entity to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control and sanctions
    text: You may not access or use the Website in violation of applicable export control, trade embargo, or sanctions laws.
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
name: ai&
provenance_date: '2026-11-09'
provider_name: ai&
provider_slug: aiand-com
slug: aiand-com-eligibility
source_date: '2026-11-09'
source_filename: aiand-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.aiand.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ai&\naid: aiand-com\nurl: https://www.aiand.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Website on behalf of a company or other entity, you represent and warrant that you have authority\n    to bind that entity to these Terms.\nrestricted_uses:\n- summary: Export control and sanctions\n  text: You may not access or use the Website in violation of applicable export control, trade embargo, or sanctions\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aiand-com/eligibility/aiand-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from ai&'s own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Japan
- Inference
- Machine Learning
- Startups
---
