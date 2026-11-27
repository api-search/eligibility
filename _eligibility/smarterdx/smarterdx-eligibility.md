---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the individual accessing this Site
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial purpose not authorized
    text: for any commercial purpose not expressly authorized by SmarterDx
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Certain areas of the Site may be accessible only to individuals who have registered and been approved for access
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SmarterDx
provenance_date: '2026-11-10'
provider_name: SmarterDx
provider_slug: smarterdx
slug: smarterdx-eligibility
source_date: '2026-11-10'
source_filename: smarterdx-eligibility.yml
source_heading: Eligibility
source_page: https://www.smarterdx.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SmarterDx\naid: smarterdx\nurl: https://www.smarterdx.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the individual accessing this Site\nrestricted_uses:\n- summary: Commercial purpose not authorized\n  text: for any commercial purpose not expressly authorized by SmarterDx\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Certain areas of the Site may be accessible only to individuals who have registered and been approved for\n    access\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smarterdx/eligibility/smarterdx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from SmarterDx's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Clinical AI
- Revenue Cycle Management
- Health Systems
- Clinical Documentation
- HIPAA
- Artificial Intelligence
---
