---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - MX
    text: The Services are based in the United States, Mexico, and in the future may include Colombia Canada, Brazil, Argentina, Chile, Peru, Uruguay, Paraguay, Venezuela, Bolivia, Ecuador, Guatemala, Honduras, El Salvador, Belize, Nicaragua, Costa Rica and Panama
  entity_types:
  - text: We hereby permit you to use the Services for your personal, non-commercial, entertainment use only
    type: individual
  minimum_age:
    text: You must be 14 years of age or older to use the Services.
    value: '14'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To activate and maintain the Student Plan, you must provide sufficient information to verify student status — including your name, institution, date of birth, and a valid educational email or documents.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TREBEL Music
provenance_date: '2026-11-10'
provider_name: TREBEL Music
provider_slug: trebel-music
slug: trebel-music-eligibility
source_date: '2026-11-10'
source_filename: trebel-music-eligibility.yml
source_heading: Eligibility
source_page: https://home.trebel.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TREBEL Music\naid: trebel-music\nurl: https://home.trebel.io/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - MX\n  excluded: []\n  text: The Services are based in the United States, Mexico, and in the future may include Colombia Canada, Brazil,\n    Argentina, Chile, Peru, Uruguay, Paraguay, Venezuela, Bolivia, Ecuador, Guatemala, Honduras, El Salvador, Belize,\n    Nicaragua, Costa Rica and Panama\nentity_types:\n- type: individual\n  text: We hereby permit you to use the Services for your personal, non-commercial, entertainment use only\nrestricted_uses: []\nverification:\n \
  \ kyc: null\n  kyb: null\n  approval_required: null\n  text: To activate and maintain the Student Plan, you must provide sufficient information to verify student status\n    — including your name, institution, date of birth, and a valid educational email or documents.\nminimum_age:\n  value: '14'\n  text: You must be 14 years of age or older to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/trebel-music/eligibility/trebel-music-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from TREBEL Music's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Music
- Music Streaming
- Media
- Entertainment
- Mobile App
- Advertising
- Consumer
---
