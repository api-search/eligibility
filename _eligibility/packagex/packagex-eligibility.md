---
api_specs:
- filename: packagex-shipments-api-openapi.yml
  format: yaml
  label: PackageX Shipments API
  slug: packagex-shipments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/packagex/openapi/packagex-shipments-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Customer agrees and acknowledges that all use of the Subscription Service by it and its End Users will occur in the United States of America (USA).
  entity_types:
  - text: the party identified in the Order Form (“Licensee” or “Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use must comply with law
    text: Customer represents and warrants that it will, and will require that its End Users, use the Services only in accordance with all applicable laws.
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
name: PackageX
provenance_date: '2026-11-10'
provider_name: PackageX
provider_slug: packagex
slug: packagex-eligibility
source_date: '2026-11-10'
source_filename: packagex-eligibility.yml
source_heading: Eligibility
source_page: https://packagex.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PackageX\naid: packagex\nurl: https://packagex.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Customer agrees and acknowledges that all use of the Subscription Service by it and its End Users will occur\n    in the United States of America (USA).\nentity_types:\n- type: business\n  text: the party identified in the Order Form (“Licensee” or “Customer”)\nrestricted_uses:\n- summary: Use must comply with law\n  text: Customer represents and warrants that it will, and will require that its End Users, use the Services only\n    in accordance with all applicable laws.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/packagex/eligibility/packagex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from PackageX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Supply Chain
- Computer Vision
- OCR
- Package Tracking
- Fulfillment
---
