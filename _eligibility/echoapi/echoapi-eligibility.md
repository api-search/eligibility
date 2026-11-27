---
api_specs:
- filename: echoapi-anything-api-openapi.yml
  format: yaml
  label: EchoAPI Anything API
  slug: echoapi-anything-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/echoapi/openapi/echoapi-anything-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing to these Terms not as an individual but on behalf of your company, government, or other entity for which you are acting
    type: business
  minimum_age:
    text: The Services are not intended for and should not be used by anyone under the age of 13, (or 18 for Users in the European Union)
    value: '13'
  restricted_uses:
  - summary: No sensitive personal information
    text: Upload any Sensitive Personal Information* into the Services
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
name: EchoAPI
provenance_date: '2026-11-09'
provider_name: EchoAPI
provider_slug: echoapi
slug: echoapi-eligibility
source_date: '2026-11-09'
source_filename: echoapi-eligibility.yml
source_heading: Eligibility
source_page: https://www.echoapi.com/wiki/docs/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EchoAPI\naid: echoapi\nurl: https://www.echoapi.com/wiki/docs/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing to these Terms not as an individual but on behalf of your company, government, or other\n    entity for which you are acting\nrestricted_uses:\n- summary: No sensitive personal information\n  text: Upload any Sensitive Personal Information* into the Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are\
  \ not intended for and should not be used by anyone under the age of 13, (or 18 for Users\n    in the European Union)\n"
source_yaml_url: https://artifacts.apis.io/echoapi/eligibility/echoapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from EchoAPI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Platform
- Integration
- Developer Tools
- Documentation
---
