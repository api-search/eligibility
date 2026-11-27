---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: You, whether personally or on behalf of an entity (“You”)
    type: business
  minimum_age:
    text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: You will not use the Site for any illegal or unauthorized purpose
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
name: Mihup
provenance_date: '2026-11-10'
provider_name: Mihup
provider_slug: mihup
slug: mihup-eligibility
source_date: '2026-11-10'
source_filename: mihup-eligibility.yml
source_heading: Eligibility
source_page: https://mihup.ai/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mihup\naid: mihup\nurl: https://mihup.ai/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: business\n  text: You, whether personally or on behalf of an entity (“You”)\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: You will not use the Site for any illegal or unauthorized purpose\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All users who are minors in the jurisdiction in which they reside (generally under the age of 18) must have\n    the permission of, and be directly supervised by, their parent or guardian to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/mihup/eligibility/mihup-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mihup's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Voice AI
- Speech Recognition
- Speech Analytics
- Conversational AI
- Contact Center
- Automotive
- Natural Language Understanding
- Text-to-Speech
---
