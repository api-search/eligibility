---
api_specs:
- filename: limble-cmms-routes-api-openapi.yml
  format: yaml
  label: Limble CMMS Routes API
  slug: limble-cmms-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/limble-cmms/openapi/limble-cmms-routes-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Hazardous use
    text: SUBSCRIPTION SERVICES ARE NOT INTENDED, LICENSED, OR PROVIDED FOR ANY HAZARDOUS USE OR ANY APPLICATION REQUIRING FDA OR OTHER GOVERNMENT APPROVAL THAT HAS NOT BEEN OBTAINED BY CUSTOMER.
  - summary: Sensitive personal data
    text: Customer must not enter or transmit, and Subscription Services are not intended to process, any data or information of a sensitive nature
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
name: Limble CMMS
provenance_date: '2026-11-09'
provider_name: Limble CMMS
provider_slug: limble-cmms
slug: limble-cmms-eligibility
source_date: '2026-11-09'
source_filename: limble-cmms-eligibility.yml
source_heading: Eligibility
source_page: https://limble.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Limble CMMS\naid: limble-cmms\nurl: https://limble.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Hazardous use\n  text: SUBSCRIPTION SERVICES ARE NOT INTENDED, LICENSED, OR PROVIDED FOR ANY HAZARDOUS USE OR ANY APPLICATION REQUIRING\n    FDA OR OTHER GOVERNMENT APPROVAL THAT HAS NOT BEEN OBTAINED BY CUSTOMER.\n- summary: Sensitive personal data\n  text: Customer must not enter or transmit, and Subscription Services are not intended to process, any data or\n    information of a sensitive nature\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/limble-cmms/eligibility/limble-cmms-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Limble CMMS's own page on 2026-11-09.
synthetic: false
tags:
- CMMS
- Maintenance Management
- Asset Management
- Manufacturing
- Facility Management
- Work Orders
---
