---
api_specs:
- filename: woox-account-api-openapi.yml
  format: yaml
  label: WOO X Account API
  slug: woox-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-account-api-openapi.yml
- filename: woox-asset-api-openapi.yml
  format: yaml
  label: WOO X Asset API
  slug: woox-asset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-asset-api-openapi.yml
- filename: woox-futures-api-openapi.yml
  format: yaml
  label: WOO X Futures API
  slug: woox-futures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-futures-api-openapi.yml
- filename: woox-isolatedmargin-api-openapi.yml
  format: yaml
  label: WOO X Isolated Margin API
  slug: woox-isolatedmargin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-isolatedmargin-api-openapi.yml
- filename: woox-public-api-openapi.yml
  format: yaml
  label: WOO X Public API
  slug: woox-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-public-api-openapi.yml
- filename: woox-spotmargin-api-openapi.yml
  format: yaml
  label: WOO X Spot Margin API
  slug: woox-spotmargin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-spotmargin-api-openapi.yml
- filename: woox-trade-api-openapi.yml
  format: yaml
  label: WOO X Trade API
  slug: woox-trade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-trade-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: Our Services are not offered to entities or persons who have their registered office or place of residence in the United States of America or any Restricted Territory as defined in Section 37.
  entity_types:
  - text: If you are registering to use the Services as an individual, you must be legally of age, depending on the jurisdiction of your nationality
    type: individual
  - text: If you are registering to use the Services on behalf of a legal entity, you represent and warrant that (i) such legal entity is duly organized and validly existing
    type: business
  minimum_age:
    text: you must not be under 18 years old
    value: '18'
  restricted_uses:
  - summary: Illegal or inappropriate activity
    text: you will not be using the Services for any illegal activity or inappropriate activity including, but not limited to, those Restricted Activities listed under Section 19.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: WOO X
provenance_date: '2026-11-10'
provider_name: WOO X
provider_slug: woox
slug: woox-eligibility
source_date: '2026-11-10'
source_filename: woox-eligibility.yml
source_heading: Eligibility
source_page: https://support.woox.io/hc/en-us/articles/4403851854233--Terms-of-Services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WOO X\naid: woox\nurl: https://support.woox.io/hc/en-us/articles/4403851854233--Terms-of-Services\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  text: Our Services are not offered to entities or persons who have their registered office or place of residence\n    in the United States of America or any Restricted Territory as defined in Section 37.\nentity_types:\n- type: individual\n  text: If you are registering to use the Services as an individual, you must be legally of age, depending on the\n    jurisdiction of your nationality\n- type: business\n  text: If\
  \ you are registering to use the Services on behalf of a legal entity, you represent and warrant that (i)\n    such legal entity is duly organized and validly existing\nrestricted_uses:\n- summary: Illegal or inappropriate activity\n  text: you will not be using the Services for any illegal activity or inappropriate activity including, but not\n    limited to, those Restricted Activities listed under Section 19.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must not be under 18 years old\n"
source_yaml_url: https://artifacts.apis.io/woox/eligibility/woox-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from WOO X's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Derivatives
---
