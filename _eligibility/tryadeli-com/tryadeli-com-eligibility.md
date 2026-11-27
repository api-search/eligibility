---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are agreeing on behalf of a company or other organization, you represent that you have authority to bind it, and "you" means that organization.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
  restricted_uses:
  - summary: Surveillance and eligibility decisions
    text: Use platform data obtained through the Service for surveillance, or to make decisions about a person's eligibility for credit, insurance, employment, housing, or a similar benefit
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
name: Adeli
provenance_date: '2026-11-10'
provider_name: Adeli
provider_slug: tryadeli-com
slug: tryadeli-com-eligibility
source_date: '2026-11-10'
source_filename: tryadeli-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.tryadeli.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Adeli\naid: tryadeli-com\nurl: https://www.tryadeli.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are agreeing on behalf of a company or other organization, you represent that you have authority\n    to bind it, and \"you\" means that organization.\nrestricted_uses:\n- summary: Surveillance and eligibility decisions\n  text: Use platform data obtained through the Service for surveillance, or to make decisions about a person's eligibility\n    for credit, insurance, employment, housing, or a similar benefit\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/tryadeli-com/eligibility/tryadeli-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Adeli's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Advertising
- Marketing
- Automation
---
