---
api_specs:
- filename: gotolstoy-com-ai-tools-api-openapi.yml
  format: yaml
  label: gotolstoy-com AI Tools API
  slug: gotolstoy-com-ai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotolstoy-com/openapi/gotolstoy-com-ai-tools-api-openapi.yml
- filename: gotolstoy-com-products-api-openapi.yml
  format: yaml
  label: gotolstoy-com Products API
  slug: gotolstoy-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotolstoy-com/openapi/gotolstoy-com-products-api-openapi.yml
- filename: gotolstoy-com-stores-api-openapi.yml
  format: yaml
  label: gotolstoy-com Stores API
  slug: gotolstoy-com-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotolstoy-com/openapi/gotolstoy-com-stores-api-openapi.yml
- filename: gotolstoy-com-studio-api-openapi.yml
  format: yaml
  label: gotolstoy-com Studio API
  slug: gotolstoy-com-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotolstoy-com/openapi/gotolstoy-com-studio-api-openapi.yml
- filename: gotolstoy-com-video-api-openapi.yml
  format: yaml
  label: gotolstoy-com Video API
  slug: gotolstoy-com-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gotolstoy-com/openapi/gotolstoy-com-video-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals over the age of eighteen (18) years.
    type: individual
  - text: These Terms are between Tolstoy and you, either individually, or on behalf of your employer or any other entity which you represent
    type: business
  minimum_age:
    text: The Site is only intended for individuals over the age of eighteen (18) years.
    value: '18'
  restricted_uses:
  - summary: Competitive purposes
    text: use the Site for competitive purposes
  - summary: Violating third-party rights
    text: use the Site in a manner that violates or infringes any rights of any third party
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
name: gotolstoy-com
provenance_date: '2026-11-09'
provider_name: gotolstoy-com
provider_slug: gotolstoy-com
slug: gotolstoy-com-eligibility
source_date: '2026-11-09'
source_filename: gotolstoy-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.gotolstoy.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: gotolstoy-com\naid: gotolstoy-com\nurl: https://www.gotolstoy.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals over the age of eighteen (18) years.\n- type: business\n  text: These Terms are between Tolstoy and you, either individually, or on behalf of your employer or any other\n    entity which you represent\nrestricted_uses:\n- summary: Competitive purposes\n  text: use the Site for competitive purposes\n- summary: Violating third-party rights\n  text: use the Site in a manner\
  \ that violates or infringes any rights of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is only intended for individuals over the age of eighteen (18) years.\n"
source_yaml_url: https://artifacts.apis.io/gotolstoy-com/eligibility/gotolstoy-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from gotolstoy-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- E-Commerce
- Platform
- Automation
- Marketing
---
