---
api_specs:
- filename: nowsta-clients-api-openapi.yml
  format: yaml
  label: Nowsta Clients API
  slug: nowsta-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nowsta/openapi/nowsta-clients-api-openapi.yml
- filename: nowsta-events-api-openapi.yml
  format: yaml
  label: Nowsta Events API
  slug: nowsta-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nowsta/openapi/nowsta-events-api-openapi.yml
- filename: nowsta-positions-api-openapi.yml
  format: yaml
  label: Nowsta Positions API
  slug: nowsta-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nowsta/openapi/nowsta-positions-api-openapi.yml
- filename: nowsta-uniforms-api-openapi.yml
  format: yaml
  label: Nowsta Uniforms API
  slug: nowsta-uniforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nowsta/openapi/nowsta-uniforms-api-openapi.yml
- filename: nowsta-venues-api-openapi.yml
  format: yaml
  label: Nowsta Venues API
  slug: nowsta-venues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nowsta/openapi/nowsta-venues-api-openapi.yml
- filename: nowsta-workers-api-openapi.yml
  format: yaml
  label: Nowsta Workers API
  slug: nowsta-workers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nowsta/openapi/nowsta-workers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Platform are solely directed to individuals, companies, or other entities located in the United States.
  minimum_age:
    text: Any use or access to the Platform by anyone under 13 (or under 16 in Europe) is strictly prohibited
    value: '18'
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
name: Nowsta
provenance_date: '2026-11-10'
provider_name: Nowsta
provider_slug: nowsta
slug: nowsta-eligibility
source_date: '2026-11-10'
source_filename: nowsta-eligibility.yml
source_heading: Eligibility
source_page: https://www.nowsta.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nowsta\naid: nowsta\nurl: https://www.nowsta.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Platform are solely directed to individuals,\n    companies, or other entities located in the United States.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Any use or access to the Platform by anyone under 13 (or under 16 in Europe) is strictly prohibited\n"
source_yaml_url: https://artifacts.apis.io/nowsta/eligibility/nowsta-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Nowsta's own page on 2026-11-10.
synthetic: false
tags:
- Workforce Management
- staff-scheduling
- shift-scheduling
- Time and Attendance
- Hourly Workforce
- GigWork
- event-staffing
- Hospitality
- staffing-agency
- Vendor Management
- Payroll
- Human Resources
---
