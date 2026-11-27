---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use by persons located in the United States.
  entity_types:
  - text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Service, unless your use thereof will only include reading our webcomic products, in which case you must be at least 13 years of age.
    value: '18'
  restricted_uses:
  - summary: Substitute for licensed professional advice
    text: any content with the intention to act as a substitute for any licensed profession, including but not limited to legal advice, financial advice, medical advice
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
name: VoyceMe
provenance_date: '2026-11-10'
provider_name: VoyceMe
provider_slug: voyceme
slug: voyceme-eligibility
source_date: '2026-11-10'
source_filename: voyceme-eligibility.yml
source_heading: Eligibility
source_page: https://www.voyce.me/pages/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VoyceMe\naid: voyceme\nurl: https://www.voyce.me/pages/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use by persons located in the United States.\nentity_types:\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant\n    that you have the authority to bind that organization to these Terms\nrestricted_uses:\n- summary: Substitute for licensed professional advice\n  text: any content with the intention to act as a substitute for any licensed profession, including\
  \ but not limited\n    to legal advice, financial advice, medical advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service, unless your use thereof will only include reading\n    our webcomic products, in which case you must be at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/voyceme/eligibility/voyceme-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from VoyceMe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Manga
- Webtoons
- Web Novels
- Comics
- Publishing
- Creators
- GraphQL
- AI Characters
- Entertainment
- Media
---
