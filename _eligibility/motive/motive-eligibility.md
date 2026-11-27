---
api_specs:
- filename: llms.txt
  format: yaml
  label: Motive Fleet API
  slug: motive-fleet-api
  spec_type: OpenAPI
  url: https://developer-docs.gomotive.com/llms.txt
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Developer will not permit use of the Motive API from a U.S. embargoed country or by any person or entity identified on OFAC’s List of Specially Designated Nationals
  entity_types:
  - text: as the individual and/or organization accessing or using a Motive Technologies, Inc. API
    type: individual
  - text: If Developer intends to use any Motive API on behalf of an organization, Developer must accept these API Terms on behalf of that organization
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Safety-critical activities
    text: Use the Motive API for any activities where the use or failure of the Motive API could lead to personal injury, death, or property damage.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: without Motive’s prior written authorization and consent (which may be withheld in Motive’s sole discretion)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Motive
provenance_date: '2026-11-10'
provider_name: Motive
provider_slug: motive
slug: motive-eligibility
source_date: '2026-11-10'
source_filename: motive-eligibility.yml
source_heading: Eligibility
source_page: https://gomotive.com/legal/api-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Motive\naid: motive\nurl: https://gomotive.com/legal/api-terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Developer will not permit use of the Motive API from a U.S. embargoed country or by any person or entity\n    identified on OFAC’s List of Specially Designated Nationals\nentity_types:\n- type: individual\n  text: as the individual and/or organization accessing or using a Motive Technologies, Inc. API\n- type: business\n  text: If Developer intends to use any Motive API on behalf of an organization, Developer must accept these API\n    Terms on behalf of that\
  \ organization\nrestricted_uses:\n- summary: Safety-critical activities\n  text: Use the Motive API for any activities where the use or failure of the Motive API could lead to personal\n    injury, death, or property damage.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: without Motive’s prior written authorization and consent (which may be withheld in Motive’s sole discretion)\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/motive/eligibility/motive-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Motive's own page on 2026-11-10.
synthetic: false
tags:
- Fleet Management
- Trucking
- Logistics
- GPS Tracking
- Hours of Service
- ELD
- IFTA
- Dash Cam
- Dispatch
- Compliance
- Driver Management
- Telematics
---
