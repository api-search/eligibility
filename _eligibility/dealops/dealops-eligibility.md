---
api_specs:
- filename: dealops-api-openapi-generated.yml
  format: yaml
  label: Dealops api API
  slug: api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealops/openapi/_ae-authored/dealops-api-openapi-generated.yml
- filename: dealops-core-openapi-generated.yml
  format: yaml
  label: Dealops core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dealops/openapi/_ae-authored/dealops-core-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents that it is not located in a country or territory that is subject to a U.S. government export embargo, or that has been sanctioned by the Office of Foreign Assets Control
  entity_types:
  - text: By entering into this agreement on behalf of a company or other legal entity, Customer represents that it has the authority to bind such entity and its affiliates to the terms of this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No Special Data
    text: Customer will not upload or request Dealops process any Special Data or otherwise use the Service in a manner that subjects Dealops to compliance requirements with laws, regulations and industry standards applicable to Special Data.
  - summary: No production use of evaluation services
    text: Evaluation Services are for Customer’s internal evaluation purposes only and not for production use
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
name: Dealops
provenance_date: '2026-11-09'
provider_name: Dealops
provider_slug: dealops
slug: dealops-eligibility
source_date: '2026-11-09'
source_filename: dealops-eligibility.yml
source_heading: Eligibility
source_page: https://dealops.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dealops\naid: dealops\nurl: https://dealops.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents that it is not located in a country or territory that is subject to a U.S. government\n    export embargo, or that has been sanctioned by the Office of Foreign Assets Control\nentity_types:\n- type: business\n  text: By entering into this agreement on behalf of a company or other legal entity, Customer represents that it\n    has the authority to bind such entity and its affiliates to the terms of this Agreement\nrestricted_uses:\n- summary: No Special\
  \ Data\n  text: Customer will not upload or request Dealops process any Special Data or otherwise use the Service in a manner\n    that subjects Dealops to compliance requirements with laws, regulations and industry standards applicable to\n    Special Data.\n- summary: No production use of evaluation services\n  text: Evaluation Services are for Customer’s internal evaluation purposes only and not for production use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dealops/eligibility/dealops-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Dealops's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CPQ
- Pricing
- Artificial Intelligence
- Software-as-a-Service
- Revenue Optimization
---
