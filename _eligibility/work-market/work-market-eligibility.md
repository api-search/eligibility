---
api_specs:
- filename: work-market-assignments-api-openapi.yml
  format: yaml
  label: Work Market Assignments API
  slug: work-market-assignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-assignments-api-openapi.yml
- filename: work-market-authorization-api-openapi.yml
  format: yaml
  label: Work Market Authorization API
  slug: work-market-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-authorization-api-openapi.yml
- filename: work-market-constants-api-openapi.yml
  format: yaml
  label: Work Market Constants API
  slug: work-market-constants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-constants-api-openapi.yml
- filename: work-market-custom-fields-api-openapi.yml
  format: yaml
  label: Work Market Custom Fields API
  slug: work-market-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-custom-fields-api-openapi.yml
- filename: work-market-labels-api-openapi.yml
  format: yaml
  label: Work Market Labels API
  slug: work-market-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-labels-api-openapi.yml
- filename: work-market-locations-api-openapi.yml
  format: yaml
  label: Work Market Locations API
  slug: work-market-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-locations-api-openapi.yml
- filename: work-market-projects-api-openapi.yml
  format: yaml
  label: Work Market Projects API
  slug: work-market-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-projects-api-openapi.yml
- filename: work-market-talent-pools-api-openapi.yml
  format: yaml
  label: Work Market Talent Pools API
  slug: work-market-talent-pools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-talent-pools-api-openapi.yml
- filename: work-market-updatecheckin-api-openapi.yml
  format: yaml
  label: Work Market UpdateCheckIn API
  slug: work-market-updatecheckin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-updatecheckin-api-openapi.yml
- filename: work-market-address-book-api-openapi.yml
  format: yaml
  label: Work Market Address Book API
  slug: work-market-address-book-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/work-market/openapi/work-market-address-book-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the WorkMarket Platform only if you can form legally binding contracts under applicable law and either have reached the age of majority or legal age in your jurisdiction (generally 18 or older) or are not an individual natural person.
    type: individual
  - text: you will only use the WorkMarket Platform and Account for business purposes
    type: business
  minimum_age:
    text: generally 18 or older
    value: '18'
  restricted_uses:
  - summary: Business purposes only
    text: will not use the WorkMarket Platform or Account for personal, family, household, or consumer purposes
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
name: Work Market
provenance_date: '2026-11-10'
provider_name: Work Market
provider_slug: work-market
slug: work-market-eligibility
source_date: '2026-11-10'
source_filename: work-market-eligibility.yml
source_heading: Eligibility
source_page: https://www.workmarket.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Work Market\naid: work-market\nurl: https://www.workmarket.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the WorkMarket Platform only if you can form legally binding contracts under applicable law\n    and either have reached the age of majority or legal age in your jurisdiction (generally 18 or older) or are\n    not an individual natural person.\n- type: business\n  text: you will only use the WorkMarket Platform and Account for business purposes\nrestricted_uses:\n- summary: Business purposes\
  \ only\n  text: will not use the WorkMarket Platform or Account for personal, family, household, or consumer purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: generally 18 or older\n"
source_yaml_url: https://artifacts.apis.io/work-market/eligibility/work-market-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Work Market's own page on 2026-11-10.
synthetic: false
tags:
- Workforce Management
- Contractors
- Freelance
- Gig Economy
- Human Resources
- Payments
- Field Service Management
- Staffing
---
