---
api_specs:
- filename: momentum-openapi-generated.yml
  format: yaml
  label: Momentum API
  slug: momentum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/momentum/openapi/_ae-authored/momentum-openapi-generated.yml
- filename: momentum-meeting-api-openapi.yml
  format: yaml
  label: Momentum Meeting API
  slug: momentum-meeting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/momentum/openapi/momentum-meeting-api-openapi.yml
- filename: momentum-momentum-api-api-openapi.yml
  format: yaml
  label: Momentum Momentum API
  slug: momentum-momentum-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/momentum/openapi/momentum-momentum-api-api-openapi.yml
- filename: momentum-signals-api-openapi.yml
  format: yaml
  label: Momentum Signals API
  slug: momentum-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/momentum/openapi/momentum-signals-api-openapi.yml
- filename: momentum-user-provided-meeting-api-openapi.yml
  format: yaml
  label: Momentum User Provided Meeting API
  slug: momentum-user-provided-meeting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/momentum/openapi/momentum-user-provided-meeting-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer is an entity, organization, or company, the individual who accepts this Agreement on Customer's behalf certifies and guarantees that they possess the authority to legally bind Customer entity to this Agreement
    type: business
  minimum_age:
    text: If Customer is under 18 years of age, Customer is not authorized to use the Service, with or without registering.
    value: '18'
  restricted_uses:
  - summary: Competitors barred from access
    text: No employee, independent contractor, agent, or affiliate of any competing company of Momentum is permitted to view, access, or use any portion of the Service without express written permission from Momentum.
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
name: Momentum
provenance_date: '2026-11-10'
provider_name: Momentum
provider_slug: momentum
slug: momentum-eligibility
source_date: '2026-11-10'
source_filename: momentum-eligibility.yml
source_heading: Eligibility
source_page: https://www.momentum.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Momentum\naid: momentum\nurl: https://www.momentum.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If Customer is an entity, organization, or company, the individual who accepts this Agreement on Customer's\n    behalf certifies and guarantees that they possess the authority to legally bind Customer entity to this Agreement\nrestricted_uses:\n- summary: Competitors barred from access\n  text: No employee, independent contractor, agent, or affiliate of any competing company of Momentum is permitted\n    to view, access,\
  \ or use any portion of the Service without express written permission from Momentum.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If Customer is under 18 years of age, Customer is not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/momentum/eligibility/momentum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Momentum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Revenue
- Automation
- Salesforce
---
