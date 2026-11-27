---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Consumers may use it, and where they do, the consumer protection rules of their country of residence apply in addition to these terms
    type: individual
  - text: The Service is designed for business use.
    type: business
  minimum_age:
    text: You must be at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons or regions
    text: you are not subject to sanctions and will not make the Service available to sanctioned persons or regions
  - summary: Documents intended to deceive
    text: you will not use the Service for the purposes listed in the Acceptable Use Policy , including documents intended to deceive
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
name: Dynamic Document API
provenance_date: '2026-11-09'
provider_name: Dynamic Document API
provider_slug: dynamicdocumentapi-com
slug: dynamicdocumentapi-com-eligibility
source_date: '2026-11-09'
source_filename: dynamicdocumentapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://dynamicdocumentapi.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dynamic Document API\naid: dynamicdocumentapi-com\nurl: https://dynamicdocumentapi.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Consumers may use it, and where they do, the consumer protection rules of their country of residence apply\n    in addition to these terms\n- type: business\n  text: The Service is designed for business use.\nrestricted_uses:\n- summary: Sanctioned persons or regions\n  text: you are not subject to sanctions and will not make the Service available to sanctioned persons or regions\n- summary:\
  \ Documents intended to deceive\n  text: you will not use the Service for the purposes listed in the Acceptable Use Policy , including documents\n    intended to deceive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/dynamicdocumentapi-com/eligibility/dynamicdocumentapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Dynamic Document API's own page on 2026-11-09.
synthetic: false
tags:
- Company
- PDF
- Image Generation
- E-Invoicing
- REST API
---
