---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is controlled and operated from facilities in the United States.
  entity_types:
  - text: the organization and/or individual agreeing to these terms (the “Customer”)
    type: individual
  - text: If an individual is entering into this Subscriber Agreement on behalf of an organization such organization shall be deemed the Customer hereunder
    type: business
  minimum_age:
    text: The Service is not authorized for use by persons under the age of 13
    value: '13'
  restricted_uses:
  - summary: Life-safety or physical-harm uses
    text: use the Service for any purpose where either the use or the failure of the Service might lead to personal injury, death or physical damage
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
name: BlueTrace
provenance_date: '2026-11-09'
provider_name: BlueTrace
provider_slug: bluetrace
slug: bluetrace-eligibility
source_date: '2026-11-09'
source_filename: bluetrace-eligibility.yml
source_heading: Eligibility
source_page: https://www.blue-trace.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BlueTrace\naid: bluetrace\nurl: https://www.blue-trace.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is controlled and operated from facilities in the United States.\nentity_types:\n- type: individual\n  text: the organization and/or individual agreeing to these terms (the “Customer”)\n- type: business\n  text: If an individual is entering into this Subscriber Agreement on behalf of an organization such organization\n    shall be deemed the Customer hereunder\nrestricted_uses:\n- summary: Life-safety or physical-harm uses\n  text: use the Service\
  \ for any purpose where either the use or the failure of the Service might lead to personal\n    injury, death or physical damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Service is not authorized for use by persons under the age of 13\n"
source_yaml_url: https://artifacts.apis.io/bluetrace/eligibility/bluetrace-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BlueTrace's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Seafood
- Supply Chain
- Software-as-a-Service
- Traceability
---
