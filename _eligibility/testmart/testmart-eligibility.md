---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Shipments will be made only to physical addresses within the Continental United States (CONUS).
  entity_types:
  - text: TestMart provides content and tools exclusively to support research, procurement, and education for government agencies, the military, authorized buyers, and partners.
    type: government
  minimum_age:
    text: null
    value: null
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
name: TestMart
provenance_date: '2026-11-10'
provider_name: TestMart
provider_slug: testmart
slug: testmart-eligibility
source_date: '2026-11-10'
source_filename: testmart-eligibility.yml
source_heading: Eligibility
source_page: https://www.testmart.com/terms-of-use.cfm
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TestMart\naid: testmart\nurl: https://www.testmart.com/terms-of-use.cfm\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Shipments will be made only to physical addresses within the Continental United States (CONUS).\nentity_types:\n- type: government\n  text: TestMart provides content and tools exclusively to support research, procurement, and education for government\n    agencies, the military, authorized buyers, and partners.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/testmart/eligibility/testmart-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from TestMart's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Government
- Procurement
- TestEquipment
- Marketplace
---
