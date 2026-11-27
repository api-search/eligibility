---
api_specs:
- filename: enable-com-openapi-generated.yml
  format: yaml
  label: Enable API
  slug: enable-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/enable-com/openapi/_ae-authored/enable-com-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If Customer is located in the United States of America, disputes go to arbitration; if not located in the United States of America, a different arbitration rule applies. No country-based service eligibility is stated.
  entity_types:
  - text: IF YOU ARE USING ANY ENABLE SERVICES AS AN EMPLOYEE, CONTRACTOR, OR AGENT OF A CORPORATION, PARTNERSHIP OR OTHER ENTITY, THEN YOU MUST BE AUTHORIZED TO SIGN FOR AND BIND SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Sensitive Information
    text: Customer will not use the Services to submit, transmit, or store Sensitive Information
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
name: Enable
provenance_date: '2026-11-09'
provider_name: Enable
provider_slug: enable-com
slug: enable-com-eligibility
source_date: '2026-11-09'
source_filename: enable-com-eligibility.yml
source_heading: Eligibility
source_page: https://developers.enable.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Enable\naid: enable-com\nurl: https://developers.enable.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If Customer is located in the United States of America, disputes go to arbitration; if not located in the\n    United States of America, a different arbitration rule applies. No country-based service eligibility is stated.\nentity_types:\n- type: business\n  text: IF YOU ARE USING ANY ENABLE SERVICES AS AN EMPLOYEE, CONTRACTOR, OR AGENT OF A CORPORATION, PARTNERSHIP\n    OR OTHER ENTITY, THEN YOU MUST BE AUTHORIZED TO SIGN FOR AND BIND SUCH ENTITY\nrestricted_uses:\n\
  - summary: No Sensitive Information\n  text: Customer will not use the Services to submit, transmit, or store Sensitive Information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/enable-com/eligibility/enable-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Enable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Pricing
- Rebate
- Software-as-a-Service
---
