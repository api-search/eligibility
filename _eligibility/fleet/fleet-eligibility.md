---
api_specs:
- filename: fleet-fleet-api-openapi.yml
  format: yaml
  label: Fleet API
  slug: fleet-fleet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fleet/openapi/fleet-fleet-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: to countries as to which the United States maintains an embargo (collectively, “Embargoed Countries”)
  entity_types:
  - text: If you are executing this agreement on behalf of an organization, you represent that you have the authority to do so.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: use the Licensed Materials in connection with any high risk or strict liability activity
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
name: Fleet
provenance_date: '2026-11-09'
provider_name: Fleet
provider_slug: fleet
slug: fleet-eligibility
source_date: '2026-11-09'
source_filename: fleet-eligibility.yml
source_heading: Eligibility
source_page: https://fleetdm.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fleet\naid: fleet\nurl: https://fleetdm.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: to countries as to which the United States maintains an embargo (collectively, “Embargoed Countries”)\nentity_types:\n- type: business\n  text: If you are executing this agreement on behalf of an organization, you represent that you have the authority\n    to do so.\nrestricted_uses:\n- summary: High-risk activities\n  text: use the Licensed Materials in connection with any high risk or strict liability activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fleet/eligibility/fleet-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Fleet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Device Management
- MDM
- Endpoint Security
- Vulnerability Management
- osquery
- Open Source
- DevOps
---
