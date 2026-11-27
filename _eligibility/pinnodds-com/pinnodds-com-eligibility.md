---
api_specs:
- filename: pinnodds-com-drops-api-openapi.yml
  format: yaml
  label: pinnodds-com Drops API
  slug: pinnodds-com-drops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinnodds-com/openapi/pinnodds-com-drops-api-openapi.yml
- filename: pinnodds-com-health-api-openapi.yml
  format: yaml
  label: pinnodds-com Health API
  slug: pinnodds-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinnodds-com/openapi/pinnodds-com-health-api-openapi.yml
- filename: pinnodds-com-kit-api-openapi.yml
  format: yaml
  label: pinnodds-com Kit API
  slug: pinnodds-com-kit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinnodds-com/openapi/pinnodds-com-kit-api-openapi.yml
- filename: pinnodds-com-ping-api-openapi.yml
  format: yaml
  label: pinnodds-com Ping API
  slug: pinnodds-com-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinnodds-com/openapi/pinnodds-com-ping-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service on behalf of a company or other entity, you represent that you have authority to bind that entity, and "you" refers to that entity.
    type: business
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a contract.
    value: '18'
  restricted_uses:
  - summary: Gambling legal age and lawful use
    text: You must be of legal age to gamble where you live, and you must ensure that any use you make of the data is lawful where you are.
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
name: pinnodds-com
provenance_date: '2026-11-10'
provider_name: pinnodds-com
provider_slug: pinnodds-com
slug: pinnodds-com-eligibility
source_date: '2026-11-10'
source_filename: pinnodds-com-eligibility.yml
source_heading: Eligibility
source_page: https://pinnodds.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: pinnodds-com\naid: pinnodds-com\nurl: https://pinnodds.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service on behalf of a company or other entity, you represent that you have authority to\n    bind that entity, and \"you\" refers to that entity.\nrestricted_uses:\n- summary: Gambling legal age and lawful use\n  text: You must be of legal age to gamble where you live, and you must ensure that any use you make of the data\n    is lawful where you are.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into a contract.\n"
source_yaml_url: https://artifacts.apis.io/pinnodds-com/eligibility/pinnodds-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from pinnodds-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Odds
- Real-Time
- Pinnacle
---
