---
api_specs:
- filename: landing-public-api-openapi.yml
  format: yaml
  label: Landing Public API
  slug: landing-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/landing/openapi/landing-public-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site, and the content, Services, products and incentives we may provide from time to time on and through the Site, are intended to comply with U.S. state and federal laws and regulations.
  entity_types:
  - text: You must be at least the age of majority in your state of residence, and fully able and competent to enter into and abide by the terms and conditions of these Terms
    type: individual
  - text: In the event you are registering an account for a business, organization or other legal entity, you represent and warrant that you have the authority to legally bind that entity
    type: business
  minimum_age:
    text: You must be at least the age of majority in your state of residence
    value: age of majority in state of residence
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
name: Landing
provenance_date: '2026-11-09'
provider_name: Landing
provider_slug: landing
slug: landing-eligibility
source_date: '2026-11-09'
source_filename: landing-eligibility.yml
source_heading: Eligibility
source_page: https://www.hellolanding.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Landing\naid: landing\nurl: https://www.hellolanding.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site, and the content, Services, products and incentives we may provide from time to time on and through\n    the Site, are intended to comply with U.S. state and federal laws and regulations.\nentity_types:\n- type: individual\n  text: You must be at least the age of majority in your state of residence, and fully able and competent to enter\n    into and abide by the terms and conditions of these Terms\n- type: business\n  text: In the event you are\
  \ registering an account for a business, organization or other legal entity, you represent\n    and warrant that you have the authority to legally bind that entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in state of residence\n  text: You must be at least the age of majority in your state of residence\n"
source_yaml_url: https://artifacts.apis.io/landing/eligibility/landing-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Landing's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PropTech
- Real Estate
- Rentals
- Furnished Apartments
- Corporate Housing
- Travel
- Agent-Native
- MCP
- Search
---
