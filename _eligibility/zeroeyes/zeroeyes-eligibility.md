---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: It is intended for business professionals, government representatives, school administrators, security personnel, members of the media, and other adults seeking information about ZeroEyes and its products and services.
    type: business
  - text: It is intended for business professionals, government representatives, school administrators, security personnel, members of the media, and other adults seeking information about ZeroEyes and its products and services.
    type: government
  minimum_age:
    text: other adults seeking information about ZeroEyes and its products and services.
    value: adults
  restricted_uses:
  - summary: Commercial use of website without consent
    text: Use this Website or its content for any commercial purpose without ZeroEyes’ express written consent
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
name: ZeroEyes
provenance_date: '2026-11-10'
provider_name: ZeroEyes
provider_slug: zeroeyes
slug: zeroeyes-eligibility
source_date: '2026-11-10'
source_filename: zeroeyes-eligibility.yml
source_heading: Eligibility
source_page: https://zeroeyes.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ZeroEyes\naid: zeroeyes\nurl: https://zeroeyes.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: It is intended for business professionals, government representatives, school administrators, security personnel,\n    members of the media, and other adults seeking information about ZeroEyes and its products and services.\n- type: government\n  text: It is intended for business professionals, government representatives, school administrators, security personnel,\n    members of the media, and other adults seeking information\
  \ about ZeroEyes and its products and services.\nrestricted_uses:\n- summary: Commercial use of website without consent\n  text: Use this Website or its content for any commercial purpose without ZeroEyes’ express written consent\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: adults\n  text: other adults seeking information about ZeroEyes and its products and services.\n"
source_yaml_url: https://artifacts.apis.io/zeroeyes/eligibility/zeroeyes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ZeroEyes's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Physical Security
- Artificial Intelligence
- Computer Vision
- Video Surveillance
- Weapons Detection
- Public Safety
- Education
- Government
- Smart Cities
---
