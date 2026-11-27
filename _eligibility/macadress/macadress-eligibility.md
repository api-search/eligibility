---
api_specs:
- filename: macadress-healthz-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Healthz API'
  slug: macadress-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-healthz-api-openapi.yml
- filename: macadress-mac-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Mac API'
  slug: macadress-mac-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-mac-api-openapi.yml
- filename: macadress-vendors-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Vendors API'
  slug: macadress-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-vendors-api-openapi.yml
- filename: macadress-vendor-api-openapi.yml
  format: yaml
  label: 'MAC Address Lookup: Find Vendor, OUI & Device Type Vendor API'
  slug: macadress-vendor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/macadress/openapi/macadress-vendor-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: API access requires a key, free or paid, and is subject to the requests-per-minute and per-cycle quota limits listed on the pricing page for your plan.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 'MAC Address Lookup: Find Vendor, OUI & Device Type'
provenance_date: '2026-11-10'
provider_name: 'MAC Address Lookup: Find Vendor, OUI & Device Type'
provider_slug: macadress
slug: macadress-eligibility
source_date: '2026-11-10'
source_filename: macadress-eligibility.yml
source_heading: Eligibility
source_page: https://macadress.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 'MAC Address Lookup: Find Vendor, OUI & Device Type'\naid: macadress\nurl: https://macadress.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: API access requires a key, free or paid, and is subject to the requests-per-minute and per-cycle quota limits\n    listed on the pricing page for your plan.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/macadress/eligibility/macadress-eligibility.yml
stated_fields:
- verification
summary_line: '1 quoted statement, read from MAC Address Lookup: Find Vendor, OUI & Device Type''s own page on 2026-11-10.'
synthetic: false
tags:
- Networking
- Network Access Control
- Security
- SecOps
- IoT
- Device Fleet Management
- MDM
- Reference Data
- IEEE OUI Lookup
- Developer Tools
- MCP
- Agent-Native
---
