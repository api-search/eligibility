---
api_specs:
- filename: stackin-io-openapi-generated.yml
  format: yaml
  label: stackin-io API
  slug: stackin-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stackin-io/openapi/_ae-authored/stackin-io-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Operated from Florianópolis, Brazil; no served or excluded country list stated.
  entity_types:
  - text: The account is meant for a company, represented by someone over 18 with authority to contract on its behalf.
    type: business
  minimum_age:
    text: represented by someone over 18 with authority to contract on its behalf
    value: '18'
  restricted_uses:
  - summary: Sandbox invoices have no fiscal value
    text: Invoices issued there carry no fiscal or legal value , do not work as documents, and may be discarded by the tax authorities at any time.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Issuing invoices requires a properly registered company and a valid digital certificate.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: stackin-io
provenance_date: '2026-11-10'
provider_name: stackin-io
provider_slug: stackin-io
slug: stackin-io-eligibility
source_date: '2026-11-10'
source_filename: stackin-io-eligibility.yml
source_heading: Eligibility
source_page: https://app.stackin.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: stackin-io\naid: stackin-io\nurl: https://app.stackin.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Operated from Florianópolis, Brazil; no served or excluded country list stated.\nentity_types:\n- type: business\n  text: The account is meant for a company, represented by someone over 18 with authority to contract on its behalf.\nrestricted_uses:\n- summary: Sandbox invoices have no fiscal value\n  text: Invoices issued there carry no fiscal or legal value , do not work as documents, and may be discarded by\n    the tax authorities at any time.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: Issuing invoices requires a properly registered company and a valid digital certificate.\nminimum_age:\n  value: '18'\n  text: represented by someone over 18 with authority to contract on its behalf\n"
source_yaml_url: https://artifacts.apis.io/stackin-io/eligibility/stackin-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from stackin-io's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Tax
- Brazil
- Invoicing
- Software-as-a-Service
---
