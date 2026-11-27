---
api_specs:
- filename: flowmingo-flowmingo-api-api-openapi.yml
  format: yaml
  label: Flowmingo Flowmingo API
  slug: flowmingo-flowmingo-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowmingo/openapi/flowmingo-flowmingo-api-api-openapi.yml
- filename: flowmingo-scheduler-api-openapi.yml
  format: yaml
  label: Flowmingo Scheduler API
  slug: flowmingo-scheduler-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flowmingo/openapi/flowmingo-scheduler-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The data shared while utilizing the Services is not designed for dissemination to, or use by, any individual or entity in jurisdictions or countries where such sharing or usage would conflict with existing laws or regulations
  entity_types:
  - text: whether personally or on behalf of an entity ("you")
    type: individual
  minimum_age:
    text: The Services are intended for users who are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Commercial use without approval
    text: The Services may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
  - summary: Competing use
    text: Use the Services to compete with us or for any revenue-generating endeavor.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration may be necessary to access certain features of the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Flowmingo
provenance_date: '2026-11-09'
provider_name: Flowmingo
provider_slug: flowmingo
slug: flowmingo-eligibility
source_date: '2026-11-09'
source_filename: flowmingo-eligibility.yml
source_heading: Eligibility
source_page: https://flowmingo.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flowmingo\naid: flowmingo\nurl: https://flowmingo.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The data shared while utilizing the Services is not designed for dissemination to, or use by, any individual\n    or entity in jurisdictions or countries where such sharing or usage would conflict with existing laws or regulations\nentity_types:\n- type: individual\n  text: whether personally or on behalf of an entity (\"you\")\nrestricted_uses:\n- summary: Commercial use without approval\n  text: The Services may not be used in connection with any commercial endeavors\
  \ except those that are specifically\n    endorsed or approved by us.\n- summary: Competing use\n  text: Use the Services to compete with us or for any revenue-generating endeavor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration may be necessary to access certain features of the Services.\nminimum_age:\n  value: '18'\n  text: The Services are intended for users who are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/flowmingo/eligibility/flowmingo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Flowmingo's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
