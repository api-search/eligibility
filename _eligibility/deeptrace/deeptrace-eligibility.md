---
api_specs:
- filename: deeptrace-chat-api-openapi.yml
  format: yaml
  label: Deeptrace Chat API
  slug: deeptrace-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeptrace/openapi/deeptrace-chat-api-openapi.yml
- filename: deeptrace-investigations-api-openapi.yml
  format: yaml
  label: Deeptrace Investigations API
  slug: deeptrace-investigations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deeptrace/openapi/deeptrace-investigations-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
  entity_types:
  - text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
    type: individual
  - text: If you access the Services using credentials provided by a company or other entity that has a separate written agreement with Deeptrace (the “Enterprise Agreement”), you represent that you are authorized by such company or other entity (“Customer”) to use the Services.
    type: business
  minimum_age:
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials provided by Deeptrace hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
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
name: Deeptrace
provenance_date: '2026-11-09'
provider_name: Deeptrace
provider_slug: deeptrace
slug: deeptrace-eligibility
source_date: '2026-11-09'
source_filename: deeptrace-eligibility.yml
source_heading: Eligibility
source_page: https://deeptrace.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Deeptrace\naid: deeptrace\nurl: https://deeptrace.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\n- type: business\n  text: If you access the Services using credentials provided by a company or other entity that has a separate written\n    agreement with Deeptrace (the “Enterprise\
  \ Agreement”), you represent that you are authorized by such company\n    or other entity (“Customer”) to use the Services.\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials\n    provided by Deeptrace hereunder, to any country for which the United States or any other relevant jurisdiction\n    requires any export license\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/deeptrace/eligibility/deeptrace-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Deeptrace's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AIOps
- Site Reliability Engineering
- Observability
- Incident Management
- Root Cause Analysis
- Monitoring
- DevOps
- AI Agents
---
