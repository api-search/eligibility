---
api_specs:
- filename: nrouter-openapi-generated.yml
  format: yaml
  label: CloudAct API
  slug: nrouter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nrouter/openapi/_ae-authored/nrouter-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in an embargoed jurisdiction and are not on any restricted-party list
  entity_types:
  - text: If you are using the Service on behalf of an organization, you represent that you have authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Unlawful activity
    text: Engage in, facilitate, or promote any unlawful activity, including fraud, money laundering, child exploitation, or terrorism
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A one-time $100 trial credit upon verifying email and phone with no payment card required.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CloudAct
provenance_date: '2026-11-10'
provider_name: CloudAct
provider_slug: nrouter
slug: nrouter-eligibility
source_date: '2026-11-10'
source_filename: nrouter-eligibility.yml
source_heading: Eligibility
source_page: https://nrouter.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CloudAct\naid: nrouter\nurl: https://nrouter.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in an embargoed jurisdiction and are not on any restricted-party\n    list\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an organization, you represent that you have authority to bind\n    that organization to these Terms.\nrestricted_uses:\n- summary: Unlawful activity\n  text: Engage in, facilitate, or promote any unlawful activity, including fraud, money laundering, child exploitation,\n    or terrorism\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: A one-time $100 trial credit upon verifying email and phone with no payment card required.\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/nrouter/eligibility/nrouter-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CloudAct's own page on 2026-11-10.
synthetic: false
tags:
- Company
- LLM Gateway
- AI Infrastructure
- Smart Routing
- Token Management
---
