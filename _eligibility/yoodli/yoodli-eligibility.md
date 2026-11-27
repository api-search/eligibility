---
api_specs:
- filename: yoodli-multi-org-management-api-openapi.yml
  format: yaml
  label: Yoodli Multi Org Management API
  slug: yoodli-multi-org-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoodli/openapi/yoodli-multi-org-management-api-openapi.yml
- filename: yoodli-organization-user-management-api-openapi.yml
  format: yaml
  label: Yoodli Organization User Management API
  slug: yoodli-organization-user-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoodli/openapi/yoodli-organization-user-management-api-openapi.yml
- filename: yoodli-speech-api-openapi.yml
  format: yaml
  label: Yoodli Speech API
  slug: yoodli-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoodli/openapi/yoodli-speech-api-openapi.yml
- filename: yoodli-user-group-management-api-openapi.yml
  format: yaml
  label: Yoodli User Group Management API
  slug: yoodli-user-group-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoodli/openapi/yoodli-user-group-management-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Website from any territory where the content is illegal is prohibited.
  entity_types:
  - text: This Website is offered and available to users who are 18 years of age or older.
    type: individual
  - text: If you are entering into this contract on behalf of a company or other legal entity, you represent that you have the authority to bind such company or entity to these Terms of Use
    type: business
  minimum_age:
    text: This Website is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Website only for lawful purposes and in accordance with these Terms of Use.
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
name: Yoodli
provenance_date: '2026-11-10'
provider_name: Yoodli
provider_slug: yoodli
slug: yoodli-eligibility
source_date: '2026-11-10'
source_filename: yoodli-eligibility.yml
source_heading: Eligibility
source_page: https://yoodli.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yoodli\naid: yoodli\nurl: https://yoodli.ai/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Website from any territory where the content is illegal is prohibited.\nentity_types:\n- type: individual\n  text: This Website is offered and available to users who are 18 years of age or older.\n- type: business\n  text: If you are entering into this contract on behalf of a company or other legal entity, you represent that\n    you have the authority to bind such company or entity to these Terms of Use\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may\
  \ use the Website only for lawful purposes and in accordance with these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/yoodli/eligibility/yoodli-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Yoodli's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Communications
- Coaching
- Learning and Development
- Sales Enablement
- Speech Analysis
- Human Resources
- Enterprise Software
- Software-as-a-Service
---
