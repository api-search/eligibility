---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept this Agreement or use the Authentic8 Service on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to this Agreement.
    type: business
  minimum_age:
    text: The Authentic8 Service is intended solely for persons who are 18 or older.
    value: '18'
  restricted_uses:
  - summary: Illegal or rights-infringing use
    text: (3) use the Authentic8 Service to support any activity that is illegal or that violates the proprietary or contractual rights of others
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
name: Authentic8
provenance_date: '2026-11-09'
provider_name: Authentic8
provider_slug: authentic8
slug: authentic8-eligibility
source_date: '2026-11-09'
source_filename: authentic8-eligibility.yml
source_heading: Eligibility
source_page: https://authentic8.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Authentic8\naid: authentic8\nurl: https://authentic8.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept this Agreement or use the Authentic8 Service on behalf of a company or other legal entity,\n    you represent and warrant that you have the authority to bind that company or other legal entity to this Agreement.\nrestricted_uses:\n- summary: Illegal or rights-infringing use\n  text: (3) use the Authentic8 Service to support any activity that is illegal or that violates the proprietary\n    or contractual\
  \ rights of others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Authentic8 Service is intended solely for persons who are 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/authentic8/eligibility/authentic8-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Authentic8's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Secure Browser
- Threat Intelligence
- Digital Investigations
- Managed Attribution
- Dark Web
---
