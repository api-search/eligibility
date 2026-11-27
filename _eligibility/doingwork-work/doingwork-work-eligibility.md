---
api_specs:
- filename: doingwork-work-status-api-openapi.yml
  format: yaml
  label: doingwork-work Status API
  slug: doingwork-work-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doingwork-work/openapi/doingwork-work-status-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Doing Work is a business tool, offered only to businesses in the United States.
  entity_types:
  - text: Doing Work is a business tool, offered only to businesses in the United States.
    type: business
  minimum_age:
    text: The person who agrees must be at least 18 and have authority to bind the business
    value: '18'
  restricted_uses:
  - summary: No personal or household use by shops
    text: It is not for personal, family or household use by shops.
  - summary: No sensitive identifiers in fields
    text: Don't put Social Security numbers, driver's license numbers, full card or bank account numbers, or health information into notes, photos or other fields.
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
name: doingwork-work
provenance_date: '2026-11-09'
provider_name: doingwork-work
provider_slug: doingwork-work
slug: doingwork-work-eligibility
source_date: '2026-11-09'
source_filename: doingwork-work-eligibility.yml
source_heading: Eligibility
source_page: https://doingwork.work/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: doingwork-work\naid: doingwork-work\nurl: https://doingwork.work/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Doing Work is a business tool, offered only to businesses in the United States.\nentity_types:\n- type: business\n  text: Doing Work is a business tool, offered only to businesses in the United States.\nrestricted_uses:\n- summary: No personal or household use by shops\n  text: It is not for personal, family or household use by shops.\n- summary: No sensitive identifiers in fields\n  text: Don't put Social Security numbers, driver's license numbers, full card\
  \ or bank account numbers, or health\n    information into notes, photos or other fields.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The person who agrees must be at least 18 and have authority to bind the business\n"
source_yaml_url: https://artifacts.apis.io/doingwork-work/eligibility/doingwork-work-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from doingwork-work's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Field Service Management
- Invoicing
- Mobile
---
