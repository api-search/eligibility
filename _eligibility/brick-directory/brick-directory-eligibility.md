---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use our Services.
    value: '13'
  restricted_uses:
  - summary: Commercial use without authorization
    text: 'Commercial Use : Use our free Services for commercial purposes without authorization'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must sign in using an external identity provider (currently Google)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brick Directory
provenance_date: '2026-11-09'
provider_name: Brick Directory
provider_slug: brick-directory
slug: brick-directory-eligibility
source_date: '2026-11-09'
source_filename: brick-directory-eligibility.yml
source_heading: Eligibility
source_page: https://brick.directory/docs/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brick Directory\naid: brick-directory\nurl: https://brick.directory/docs/terms-of-service.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use our Services.\nrestricted_uses:\n- summary: Commercial use without authorization\n  text: 'Commercial Use : Use our free Services for commercial purposes without authorization'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must sign in using an external identity provider (currently Google)\nminimum_age:\n  value: '13'\n\
  \  text: You must be at least 13 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/brick-directory/eligibility/brick-directory-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Brick Directory's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LEGO
- Assistant
- MCP
---
