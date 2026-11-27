---
api_specs:
- filename: zendesk-sell.postman_collection.json
  format: json
  label: Zendesk Sell (Sales CRM) API
  slug: sales-crm-api
  spec_type: Postman
  url: https://artifacts.apis.io/zendesk-sell/collections/zendesk-sell.postman_collection.json
- filename: zendesk-sell-contacts-api-openapi.yml
  format: yaml
  label: Zendesk Sell Contacts API
  slug: zendesk-sell-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-contacts-api-openapi.yml
- filename: zendesk-sell-deals-api-openapi.yml
  format: yaml
  label: Zendesk Sell Deals API
  slug: zendesk-sell-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-deals-api-openapi.yml
- filename: zendesk-sell-leads-api-openapi.yml
  format: yaml
  label: Zendesk Sell Leads API
  slug: zendesk-sell-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-leads-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Customer represents and warrants that it, its Affiliates, and its authorized personnel: (i) are not on any U.S. government-issued list of restricted or denied persons; and (ii) are not located in any countries or territories subject to a U.S. government embargo or trade sanctions.'
  entity_types:
  - text: If Customer is a U.S. federal government department or agency or contracting on behalf of such department or agency, the Services are a “Commercial Product”
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No health data unless BAA
    text: Unless the parties have entered into a Business Associate Agreement or similar exhibit, Customer will not (and will not permit others to) store Health Data in the Services.
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
name: Zendesk Sell
provenance_date: '2026-11-10'
provider_name: Zendesk Sell
provider_slug: zendesk-sell
slug: zendesk-sell-eligibility
source_date: '2026-11-10'
source_filename: zendesk-sell-eligibility.yml
source_heading: Eligibility
source_page: https://www.zendesk.com/company/agreements-and-terms/zendesk-customer-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zendesk Sell\naid: zendesk-sell\nurl: https://www.zendesk.com/company/agreements-and-terms/zendesk-customer-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Customer represents and warrants that it, its Affiliates, and its authorized personnel: (i) are not on\n    any U.S. government-issued list of restricted or denied persons; and (ii) are not located in any countries or\n    territories subject to a U.S. government embargo or trade sanctions.'\nentity_types:\n- type: government\n  text: If Customer is a U.S. federal government department or agency or contracting on behalf\
  \ of such department\n    or agency, the Services are a “Commercial Product”\nrestricted_uses:\n- summary: No health data unless BAA\n  text: Unless the parties have entered into a Business Associate Agreement or similar exhibit, Customer will not\n    (and will not permit others to) store Health Data in the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zendesk-sell/eligibility/zendesk-sell-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Zendesk Sell's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Sales
- Sales Automation
- Leads
- Deals
- Pipelines
- Customer Experience
---
