---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If You access the Services from outside of the United States or Canada, You do so at Your own risk and are responsible for compliance with the laws of Your jurisdiction.
  entity_types:
  - text: If You are using and/or accessing the Services on behalf of a company, entity, or organization (collectively, a “Subscribing Entity”), You represent and warrant that
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age to use the Services.
    value: '18'
  restricted_uses:
  - summary: Previously removed or suspended users
    text: The Services are also not available to any users who have been previously removed or suspended from the Services.
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
name: Builder Prime
provenance_date: '2026-11-09'
provider_name: Builder Prime
provider_slug: builder-prime
slug: builder-prime-eligibility
source_date: '2026-11-09'
source_filename: builder-prime-eligibility.yml
source_heading: Eligibility
source_page: https://www.builderprime.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Builder Prime\naid: builder-prime\nurl: https://www.builderprime.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If You access the Services from outside of the United States or Canada, You do so at Your own risk and are\n    responsible for compliance with the laws of Your jurisdiction.\nentity_types:\n- type: business\n  text: If You are using and/or accessing the Services on behalf of a company, entity, or organization (collectively,\n    a “Subscribing Entity”), You represent and warrant that\nrestricted_uses:\n- summary: Previously removed or suspended users\n\
  \  text: The Services are also not available to any users who have been previously removed or suspended from the\n    Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/builder-prime/eligibility/builder-prime-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Builder Prime's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CRM
- Home Improvement
- Construction
- Contractors
- Remodeling
- Sales
- Estimating
- Project Management
- Lead Management
- Field Service Management
- Software-as-a-Service
---
