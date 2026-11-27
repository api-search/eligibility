---
api_specs:
- filename: breezy-hr-openapi-generated.yml
  format: yaml
  label: Breezy HR API
  slug: breezy-hr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/breezy-hr/openapi/_ae-authored/breezy-hr-openapi-generated.yml
- filename: breezy-hr-breezy-hr-api-api-openapi.yml
  format: yaml
  label: Breezy HR Breezy HR API
  slug: breezy-hr-breezy-hr-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/breezy-hr/openapi/breezy-hr-breezy-hr-api-api-openapi.yml
- filename: breezy-hr-sign-in-api-openapi.yml
  format: yaml
  label: Breezy HR Sign In API
  slug: breezy-hr-sign-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/breezy-hr/openapi/breezy-hr-sign-in-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals, companies, or other entities located in the United States. You may not use the Service if you are a resident of a country embargoed by the United States
  entity_types:
  - text: IF YOU ARE USING THE SERVICE ON BEHALF OF AN ORGANIZATION OR LEGAL ENTITY (“ORGANIZATION”), THEN YOU ARE AGREEING TO THESE TERMS ON BEHALF OF THAT ORGANIZATION
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI output not sole basis for decisions
    text: AI-generated content should not be used as the sole basis for any recruiting or employment decision.
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
name: Breezy HR
provenance_date: '2026-11-09'
provider_name: Breezy HR
provider_slug: breezy-hr
slug: breezy-hr-eligibility
source_date: '2026-11-09'
source_filename: breezy-hr-eligibility.yml
source_heading: Eligibility
source_page: https://breezy.hr/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Breezy HR\naid: breezy-hr\nurl: https://breezy.hr/policies/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unless otherwise explicitly stated, all materials found on the Service are solely directed to individuals,\n    companies, or other entities located in the United States. You may not use the Service if you are a resident\n    of a country embargoed by the United States\nentity_types:\n- type: business\n  text: IF YOU ARE USING THE SERVICE ON BEHALF OF AN ORGANIZATION OR LEGAL ENTITY (“ORGANIZATION”), THEN YOU ARE\n    AGREEING TO THESE TERMS ON BEHALF OF THAT ORGANIZATION\n\
  restricted_uses:\n- summary: AI output not sole basis for decisions\n  text: AI-generated content should not be used as the sole basis for any recruiting or employment decision.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/breezy-hr/eligibility/breezy-hr-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Breezy HR's own page on 2026-11-09.
synthetic: false
tags:
- Hiring
- Applicant Tracking
- Recruiting
- Software-as-a-Service
- Human Resources
---
