---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We do not guarantee that the Service is appropriate or available for use outside Mexico, and accessing or using it from territories where such use is illegal is therefore prohibited.
  entity_types:
  - text: Any individual, without distinction or reference to any gender or sexual identity, who uses the Platform and the Services offered on it.
    type: individual
  minimum_age:
    text: you are 13 (thirteen) years of age or older and have the authorization of your parents or guardians
    value: '13'
  restricted_uses:
  - summary: Recreational only, not medical
    text: Yana DOES NOT and WILL NOT offer medical or clinical advice.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must create a User Profile and authorize the necessary and sufficient permissions on your electronic device.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Yana
provenance_date: '2026-11-10'
provider_name: Yana
provider_slug: yana
slug: yana-eligibility
source_date: '2026-11-10'
source_filename: yana-eligibility.yml
source_heading: Eligibility
source_page: https://yana.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yana\naid: yana\nurl: https://yana.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We do not guarantee that the Service is appropriate or available for use outside Mexico, and accessing or\n    using it from territories where such use is illegal is therefore prohibited.\nentity_types:\n- type: individual\n  text: Any individual, without distinction or reference to any gender or sexual identity, who uses the Platform\n    and the Services offered on it.\nrestricted_uses:\n- summary: Recreational only, not medical\n  text: Yana DOES NOT and WILL NOT offer medical or clinical\
  \ advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must create a User Profile and authorize the necessary and sufficient permissions on your electronic\n    device.\nminimum_age:\n  value: '13'\n  text: you are 13 (thirteen) years of age or older and have the authorization of your parents or guardians\n"
source_yaml_url: https://artifacts.apis.io/yana/eligibility/yana-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Yana's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Emotional Wellness
- AI Companion
- Chatbots
- Mobile App
- Consumer
---
