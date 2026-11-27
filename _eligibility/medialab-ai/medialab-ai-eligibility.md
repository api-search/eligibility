---
api_specs:
- filename: medialab-ai-imgur-api.postman_collection.json
  format: json
  label: Imgur API
  slug: imgur-api
  spec_type: Postman
  url: https://artifacts.apis.io/medialab-ai/postman/medialab-ai-imgur-api.postman_collection.json
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    source: https://medialab.la/terms-of-service
    text: You must be at least 13 years of age in the US, or 16 years of age in countries subject to the EU General Data Protection Regulation (the "GDPR"), unless exempted by individual country exceptions
  entity_types:
  - text: if you are an individual and use imgur.com for personal or household use
    type: individual
  - text: Our service (including, our App, Website, and UGC) is for your personal use and may not be used for direct commercial endeavors without the express written consent of us.
    type: business
  minimum_age:
    text: Imgur is not meant for use by children under age 13
    value: '13'
  restricted_uses:
  - summary: Commercial use without written consent
    text: Our service (including, our App, Website, and UGC) is for your personal use and may not be used for direct commercial endeavors without the express written consent of us.
  - summary: AI machine learning use
    text: you agree not to use, display, distribute, license, perform, publish, reproduce, duplicate, copy, create derivative works from, modify, sell, resell, exploit (including, without limitation, for A.I. machine learning purposes)
  - source: https://medialab.la/terms-of-service
    summary: Export-controlled use
    text: You agree to comply with all applicable export and reexport control laws and regulations, including the EAR, trade and economic sanctions maintained by OFAC, and the ITAR.
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
name: MediaLab.AI
provenance_date: '2026-11-10'
provider_name: MediaLab.AI
provider_slug: medialab-ai
slug: medialab-ai-eligibility
source_date: '2026-11-10'
source_filename: medialab-ai-eligibility.yml
source_heading: Eligibility
source_page: https://imgur.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MediaLab.AI\naid: medialab-ai\nurl: https://imgur.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://imgur.com/tos\n  - https://medialab.la/terms-of-service\ncountries:\n  served: []\n  excluded: []\n  text: You must be at least 13 years of age in the US, or 16 years of age in countries subject to the EU General\n    Data Protection Regulation (the \"GDPR\"), unless exempted by individual country exceptions\n  source: https://medialab.la/terms-of-service\nentity_types:\n- type: individual\n  text: if you are an individual and use imgur.com for personal or household use\n- type: business\n  text: Our\
  \ service (including, our App, Website, and UGC) is for your personal use and may not be used for direct\n    commercial endeavors without the express written consent of us.\nrestricted_uses:\n- summary: Commercial use without written consent\n  text: Our service (including, our App, Website, and UGC) is for your personal use and may not be used for direct\n    commercial endeavors without the express written consent of us.\n- summary: AI machine learning use\n  text: you agree not to use, display, distribute, license, perform, publish, reproduce, duplicate, copy, create\n    derivative works from, modify, sell, resell, exploit (including, without limitation, for A.I. machine learning\n    purposes)\n- summary: Export-controlled use\n  text: You agree to comply with all applicable export and reexport control laws and regulations, including the\n    EAR, trade and economic sanctions maintained by OFAC, and the ITAR.\n  source: https://medialab.la/terms-of-service\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Imgur is not meant for use by children under age 13\n"
source_yaml_url: https://artifacts.apis.io/medialab-ai/eligibility/medialab-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from MediaLab.AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Social
- Advertising
- Content
- Image
- Music
- Messaging
- Community
- Holding Company
---
