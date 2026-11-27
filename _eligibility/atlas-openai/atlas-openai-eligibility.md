---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Our Services may not be used in or for the benefit of, or exported or re-exported to (a) any U.S. embargoed country or territory or (b) any individual or entity with whom dealings are prohibited or restricted under applicable trade laws.
  entity_types:
  - text: If you are a business or organization, to the extent permitted by law, you will indemnify and hold harmless us, our affiliates, and our personnel
    type: business
  minimum_age:
    text: You must be at least 13 years old or the minimum age required in your country to consent to use the Services.
    value: '13'
  restricted_uses:
  - summary: Output used for decisions about people
    text: You must not use any Output relating to a person for any purpose that could have a legal or material impact on that person
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
name: ChatGPT Atlas
provenance_date: '2026-11-09'
provider_name: ChatGPT Atlas
provider_slug: atlas-openai
slug: atlas-openai-eligibility
source_date: '2026-11-09'
source_filename: atlas-openai-eligibility.yml
source_heading: Eligibility
source_page: https://openai.com/policies/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChatGPT Atlas\naid: atlas-openai\nurl: https://openai.com/policies/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Our Services may not be used in or for the benefit of, or exported or re-exported to (a) any U.S. embargoed\n    country or territory or (b) any individual or entity with whom dealings are prohibited or restricted under applicable\n    trade laws.\nentity_types:\n- type: business\n  text: If you are a business or organization, to the extent permitted by law, you will indemnify and hold harmless\n    us, our affiliates, and our personnel\nrestricted_uses:\n\
  - summary: Output used for decisions about people\n  text: You must not use any Output relating to a person for any purpose that could have a legal or material impact\n    on that person\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old or the minimum age required in your country to consent to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/atlas-openai/eligibility/atlas-openai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ChatGPT Atlas's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Browser
- Consumer
- Agents
- Chromium
- ChatGPT
- OpenAI
---
