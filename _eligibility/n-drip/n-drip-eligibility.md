---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are accessing the Website on behalf of a company, by using the Website, You declare that You are authorized to agree to these Terms on such company’s behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or IP-violating use
    text: You may not use the Website in any manner which violates any laws, rules, regulations or policies of any applicable jurisdiction, and/or violates NDrip’s intellectual property rights.
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
name: N-Drip
provenance_date: '2026-11-10'
provider_name: N-Drip
provider_slug: n-drip
slug: n-drip-eligibility
source_date: '2026-11-10'
source_filename: n-drip-eligibility.yml
source_heading: Eligibility
source_page: https://ndrip.com/wp-content/themes/ndrip/includes/images/terms.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: N-Drip\naid: n-drip\nurl: https://ndrip.com/wp-content/themes/ndrip/includes/images/terms.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are accessing the Website on behalf of a company, by using the Website, You declare that You are\n    authorized to agree to these Terms on such company’s behalf.\nrestricted_uses:\n- summary: Unlawful or IP-violating use\n  text: You may not use the Website in any manner which violates any laws, rules, regulations or policies of any\n    applicable jurisdiction, and/or violates NDrip’s\
  \ intellectual property rights.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/n-drip/eligibility/n-drip-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from N-Drip's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agriculture
- AgTech
- Irrigation
- Water
- Water Conservation
- Sustainability
- Climate
- Precision Agriculture
- Sensors
- IoT
- Israel
---
