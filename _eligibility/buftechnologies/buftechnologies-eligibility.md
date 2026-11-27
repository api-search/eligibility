---
api_specs:
- filename: buftechnologies-connectrpc-api-openapi.yml
  format: yaml
  label: Buftechnologies Connectrpc API
  slug: buftechnologies-connectrpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buftechnologies/openapi/buftechnologies-connectrpc-api-openapi.yml
- filename: buftechnologies-foo-api-openapi.yml
  format: yaml
  label: Buftechnologies Foo API
  slug: buftechnologies-foo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buftechnologies/openapi/buftechnologies-foo-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU REGISTERED ON THE WEBSITE.
    type: individual
  - text: you have the authority to enter into the terms of use personally or on behalf of the entity you have named as the user
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract with company
    value: null
  restricted_uses:
  - summary: No false identity or accounts on behalf of others
    text: You agree not to create an Account using a false identity or information, or on behalf of someone other than yourself.
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
name: Buftechnologies
provenance_date: '2026-11-09'
provider_name: Buftechnologies
provider_slug: buftechnologies
slug: buftechnologies-eligibility
source_date: '2026-11-09'
source_filename: buftechnologies-eligibility.yml
source_heading: Eligibility
source_page: https://buf.build/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buftechnologies\naid: buftechnologies\nurl: https://buf.build/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: THE TERM “YOU” REFERS TO THE INDIVIDUAL OR LEGAL ENTITY, AS APPLICABLE, IDENTIFIED AS THE USER WHEN YOU\n    REGISTERED ON THE WEBSITE.\n- type: business\n  text: you have the authority to enter into the terms of use personally or on behalf of the entity you have named\n    as the user\nrestricted_uses:\n- summary: No false identity or accounts on behalf of others\n  text: You agree not to create an Account\
  \ using a false identity or information, or on behalf of someone other\n    than yourself.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you are of legal age to form a binding contract with company\n"
source_yaml_url: https://artifacts.apis.io/buftechnologies/eligibility/buftechnologies-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Buftechnologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Protobuf
- gRPC
- Developer Tools
---
