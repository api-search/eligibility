---
api_specs:
- filename: andiai-com-search-api-openapi.yml
  format: yaml
  label: Andi AI Search API
  slug: andiai-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/andiai-com/openapi/andiai-com-search-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Some features may be limited by location.
  entity_types:
  - text: You must be 13 or older to use Andi. If under 18, get parent/guardian permission.
    type: individual
  minimum_age:
    text: You must be 13 or older to use Andi.
    value: '13'
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
name: Andi AI
provenance_date: '2026-11-09'
provider_name: Andi AI
provider_slug: andiai-com
slug: andiai-com-eligibility
source_date: '2026-11-09'
source_filename: andiai-com-eligibility.yml
source_heading: Eligibility
source_page: https://andiai.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Andi AI\naid: andiai-com\nurl: https://andiai.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Some features may be limited by location.\nentity_types:\n- type: individual\n  text: You must be 13 or older to use Andi. If under 18, get parent/guardian permission.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be 13 or older to use Andi.\n"
source_yaml_url: https://artifacts.apis.io/andiai-com/eligibility/andiai-com-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Andi AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Search
- Privacy
- OpenAI
- Community
---
