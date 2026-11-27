---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A User means a person, entity or organisation who accesses and uses our Platform to connect to Providers whether for themselves or on behalf of others.
    type: individual
  - text: A Provider is a person or entity offering the provision of the Providers' products or services to Users on the Platform.
    type: business
  minimum_age:
    text: any person under the age of 18 is not permitted to access or use the Platform (unauthorised persons)
    value: '18'
  restricted_uses:
  - summary: Commercial purposes
    text: You must not use the Platform and any content provided by us by any means for commercial purposes
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
name: Kismet
provenance_date: '2026-11-09'
provider_name: Kismet
provider_slug: kismet
slug: kismet-eligibility
source_date: '2026-11-09'
source_filename: kismet-eligibility.yml
source_heading: Eligibility
source_page: https://www.kismet.healthcare/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kismet\naid: kismet\nurl: https://www.kismet.healthcare/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A User means a person, entity or organisation who accesses and uses our Platform to connect to Providers\n    whether for themselves or on behalf of others.\n- type: business\n  text: A Provider is a person or entity offering the provision of the Providers' products or services to Users\n    on the Platform.\nrestricted_uses:\n- summary: Commercial purposes\n  text: You must not use the Platform and any content provided by\
  \ us by any means for commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: any person under the age of 18 is not permitted to access or use the Platform (unauthorised persons)\n"
source_yaml_url: https://artifacts.apis.io/kismet/eligibility/kismet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kismet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Disability
- NDIS
- Marketplace
- Australia
- Care
- Plan Management
---
