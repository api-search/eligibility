---
api_specs:
- filename: cloro-dev-async-api-openapi.yml
  format: yaml
  label: cloro Async API
  slug: cloro-dev-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloro-dev/openapi/cloro-dev-async-api-openapi.yml
- filename: cloro-dev-countries-api-openapi.yml
  format: yaml
  label: cloro Countries API
  slug: cloro-dev-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloro-dev/openapi/cloro-dev-countries-api-openapi.yml
- filename: cloro-dev-credits-api-openapi.yml
  format: yaml
  label: cloro Credits API
  slug: cloro-dev-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloro-dev/openapi/cloro-dev-credits-api-openapi.yml
- filename: cloro-dev-monitor-api-openapi.yml
  format: yaml
  label: cloro Monitor API
  slug: cloro-dev-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloro-dev/openapi/cloro-dev-monitor-api-openapi.yml
- filename: cloro-dev-states-api-openapi.yml
  format: yaml
  label: cloro States API
  slug: cloro-dev-states-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cloro-dev/openapi/cloro-dev-states-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that you are not located in, under the control of, or a national or resident of any country or territory subject to comprehensive U.S. economic sanctions
  entity_types:
  - text: If you are using, accessing, or otherwise engaging with the Services on behalf of an organization, you represent and warrant that you have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal data of minors
    text: You shall not use the Services to access, collect, or process personal data of minors or special categories of personal data without a valid legal basis
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
name: cloro
provenance_date: '2026-11-09'
provider_name: Cloro Incorporation Ltd.
provider_slug: cloro-dev
slug: cloro-dev-eligibility
source_date: '2026-11-09'
source_filename: cloro-dev-eligibility.yml
source_heading: Eligibility
source_page: https://cloro.dev/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: cloro\naid: cloro-dev\nurl: https://cloro.dev/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that you are not located in, under the control of, or a national or resident of\n    any country or territory subject to comprehensive U.S. economic sanctions\nentity_types:\n- type: business\n  text: If you are using, accessing, or otherwise engaging with the Services on behalf of an organization, you represent\n    and warrant that you have the authority to bind that organization to these Terms.\nrestricted_uses:\n- summary: No personal data of minors\n\
  \  text: You shall not use the Services to access, collect, or process personal data of minors or special categories\n    of personal data without a valid legal basis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cloro-dev/eligibility/cloro-dev-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from cloro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Search
- Artificial Intelligence
- Web Scraping
- SERP
- Generative Engine Optimization
- SEO
- Brand Monitoring
- Market Research
- Data Extraction
- MCP
---
