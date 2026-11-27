---
api_specs:
- filename: dynamo-ai-openapi-generated.yml
  format: yaml
  label: Dynamo AI API
  slug: dynamo-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dynamo-ai/openapi/_ae-authored/dynamo-ai-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: whether personally or on behalf of an entity (“you”)
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Industry-regulated interactions (HIPAA, FISMA, GLBA)
    text: The Site is not tailored to comply with industry-specific regulations (Health Insurance Portability and Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions would be subjected to such laws, you may not use this Site.
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
name: Dynamo AI
provenance_date: '2026-11-09'
provider_name: Dynamo AI
provider_slug: dynamo-ai
slug: dynamo-ai-eligibility
source_date: '2026-11-09'
source_filename: dynamo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.dynamo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dynamo AI\naid: dynamo-ai\nurl: https://www.dynamo.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (“you”)\nrestricted_uses:\n- summary: Industry-regulated interactions (HIPAA, FISMA, GLBA)\n  text: The Site is not tailored to comply with industry-specific regulations\
  \ (Health Insurance Portability and\n    Accountability Act (HIPAA), Federal Information Security Management Act (FISMA), etc.), so if your interactions\n    would be subjected to such laws, you may not use this Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/dynamo-ai/eligibility/dynamo-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Dynamo AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Security
- Enterprise
- Compliance
---
