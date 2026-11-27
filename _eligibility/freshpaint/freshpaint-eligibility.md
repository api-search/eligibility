---
api_specs:
- filename: freshpaint-events-api-openapi.yml
  format: yaml
  label: Freshpaint Events API
  slug: freshpaint-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freshpaint/openapi/freshpaint-events-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the organization identified as the customer (the “Customer”) on the applicable Order Form
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No protected health information without a BAA
    text: Customer agrees not to use the Services to collect, store, process or transmit any patient, medical or other Protected Health Information regulated by the Health Insurance Portability and Accountability Act (“HIPAA”), unless and until a Business Associate Agreement (“BAA”) is executed and in place between Customer and Freshpaint.
  - summary: No prohibited personal information
    text: Customer specifically agrees not to use the Services to collect, store, process or transmit any Prohibited Personal Information, unless otherwise set forth in Customer’s applicable Order Form.
  - summary: No export-controlled ITAR data
    text: Customer shall not submit to the Service any information that is controlled under the U.S. International Traffic in Arms Regulations.
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
name: Freshpaint
provenance_date: '2026-11-09'
provider_name: Freshpaint
provider_slug: freshpaint
slug: freshpaint-eligibility
source_date: '2026-11-09'
source_filename: freshpaint-eligibility.yml
source_heading: Eligibility
source_page: https://www.freshpaint.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freshpaint\naid: freshpaint\nurl: https://www.freshpaint.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the organization identified as the customer (the “Customer”) on the applicable Order Form\nrestricted_uses:\n- summary: No protected health information without a BAA\n  text: Customer agrees not to use the Services to collect, store, process or transmit any patient, medical or other\n    Protected Health Information regulated by the Health Insurance Portability and Accountability Act (“HIPAA”),\n    unless and until a Business\
  \ Associate Agreement (“BAA”) is executed and in place between Customer and Freshpaint.\n- summary: No prohibited personal information\n  text: Customer specifically agrees not to use the Services to collect, store, process or transmit any Prohibited\n    Personal Information, unless otherwise set forth in Customer’s applicable Order Form.\n- summary: No export-controlled ITAR data\n  text: Customer shall not submit to the Service any information that is controlled under the U.S. International\n    Traffic in Arms Regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/freshpaint/eligibility/freshpaint-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Freshpaint's own page on 2026-11-09.
synthetic: false
tags:
- Customer Data Platform
- Event Tracking
- Healthcare
- HIPAA
- Privacy
- Analytics
---
