---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'If you are using the Via Services on behalf of any organization, agency, or corporate entity (including an Enterprise Customer), then you represent and warrant that you: (1) are an authorized representative of that organization'
    type: business
  minimum_age:
    text: No person under the age of 18 may create a User Account or use the Via Services without the consent of a parent or guardian.
    value: '18'
  restricted_uses:
  - summary: Illegal use or use where unauthorized
    text: access the Via Services from a jurisdiction where it is illegal or unauthorized
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
name: Via Transportation
provenance_date: '2026-11-10'
provider_name: Via Transportation
provider_slug: via-transportation
slug: via-transportation-eligibility
source_date: '2026-11-10'
source_filename: via-transportation-eligibility.yml
source_heading: Eligibility
source_page: https://ridewithvia.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Via Transportation\naid: via-transportation\nurl: https://ridewithvia.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 'If you are using the Via Services on behalf of any organization, agency, or corporate entity (including\n    an Enterprise Customer), then you represent and warrant that you: (1) are an authorized representative of that\n    organization'\nrestricted_uses:\n- summary: Illegal use or use where unauthorized\n  text: access the Via Services from a jurisdiction where it is illegal\
  \ or unauthorized\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: No person under the age of 18 may create a User Account or use the Via Services without the consent of a\n    parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/via-transportation/eligibility/via-transportation-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Via Transportation's own page on 2026-11-10.
synthetic: false
tags:
- Transportation
- Mobility
- On-Demand
- Public Transit
- Software
---
