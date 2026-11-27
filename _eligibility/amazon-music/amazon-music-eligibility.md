---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You (and all parties that own or control you) are not subject to sanctions or otherwise designated on any list of prohibited or restricted parties maintained by the United States government or other applicable government authority.
  entity_types:
  - text: you (if registering as an individual)
    type: individual
  - text: the entity you represent (if registering as a business)
    type: business
  minimum_age:
    text: You are at least the legal age of majority and that you are able to form a legally binding contract.
    value: legal age of majority
  restricted_uses:
  - summary: Sanctioned parties barred
    text: You (and all parties that own or control you) are not subject to sanctions or otherwise designated on any list of prohibited or restricted parties maintained by the United States government or other applicable government authority.
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
name: Amazon Music
provenance_date: '2026-11-09'
provider_name: Amazon Music
provider_slug: amazon-music
slug: amazon-music-eligibility
source_date: '2026-11-09'
source_filename: amazon-music-eligibility.yml
source_heading: Eligibility
source_page: https://developer.amazon.com/support/legal/da
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Amazon Music\naid: amazon-music\nurl: https://developer.amazon.com/support/legal/da\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: You (and all parties that own or control you) are not subject to sanctions or otherwise designated on any\n    list of prohibited or restricted parties maintained by the United States government or other applicable government\n    authority.\nentity_types:\n- type: individual\n  text: you (if registering as an individual)\n- type: business\n  text: the entity you represent (if registering as a business)\nrestricted_uses:\n- summary:\
  \ Sanctioned parties barred\n  text: You (and all parties that own or control you) are not subject to sanctions or otherwise designated on any\n    list of prohibited or restricted parties maintained by the United States government or other applicable government\n    authority.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age of majority\n  text: You are at least the legal age of majority and that you are able to form a legally binding contract.\n"
source_yaml_url: https://artifacts.apis.io/amazon-music/eligibility/amazon-music-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Amazon Music's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Streaming
- Audio
- Amazon
---
