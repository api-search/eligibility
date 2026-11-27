---
api_specs:
- filename: albacross-company-api-openapi.yml
  format: yaml
  label: Albacross Company API
  slug: albacross-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/albacross/openapi/albacross-company-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a physical person, you must be over 18 years of age (or such other legal age as may apply in your territory) in order to register an account for the Services.
    type: individual
  minimum_age:
    text: If you are a physical person, you must be over 18 years of age (or such other legal age as may apply in your territory) in order to register an account for the Services.
    value: '18'
  restricted_uses:
  - summary: Campaigns violating law or policy
    text: Albacross reserves the right to deny and/or terminate (as applicable) any Campaign which violates applicable law, Albacross’ policies or which is in any way or form inappropriate subject to Albacross’ sole assessment.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To register an account with Albacross, you will be asked to provide your email address and password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Albacross
provenance_date: '2026-11-09'
provider_name: Albacross
provider_slug: albacross
slug: albacross-eligibility
source_date: '2026-11-09'
source_filename: albacross-eligibility.yml
source_heading: Eligibility
source_page: https://www.albacross.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Albacross\naid: albacross\nurl: https://www.albacross.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a physical person, you must be over 18 years of age (or such other legal age as may apply in\n    your territory) in order to register an account for the Services.\nrestricted_uses:\n- summary: Campaigns violating law or policy\n  text: Albacross reserves the right to deny and/or terminate (as applicable) any Campaign which violates applicable\n    law, Albacross’ policies or which is in any way or form\
  \ inappropriate subject to Albacross’ sole assessment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To register an account with Albacross, you will be asked to provide your email address and password.\nminimum_age:\n  value: '18'\n  text: If you are a physical person, you must be over 18 years of age (or such other legal age as may apply in\n    your territory) in order to register an account for the Services.\n"
source_yaml_url: https://artifacts.apis.io/albacross/eligibility/albacross-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Albacross's own page on 2026-11-09.
synthetic: false
tags:
- Company
- B2B Data
- Lead Generation
- Intent Data
- Company Enrichment
- IP Intelligence
- Firmographics
- Marketing
- Sales Intelligence
- Account Based Marketing
- Website Visitor Identification
- Webhook
- Data Enrichment
---
