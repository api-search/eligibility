---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The App is intended for use by residents of the United States. By using the App, you represent that you are located in the United States.
  entity_types:
  - text: You must be at least 18 years old to use the App. If you are under 18, you may only use the App if your parent or legal guardian has reviewed and agreed to these Terms on your behalf and provides ongoing supervision of your use.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the App.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use
    text: You are granted a limited, non-exclusive, non-transferable, revocable license to use the App solely for personal, non-commercial purposes in accordance with these Terms.
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
name: Fortell
provenance_date: '2026-11-09'
provider_name: Fortell
provider_slug: fortell
slug: fortell-eligibility
source_date: '2026-11-09'
source_filename: fortell-eligibility.yml
source_heading: Eligibility
source_page: https://www.fortell.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fortell\naid: fortell\nurl: https://www.fortell.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The App is intended for use by residents of the United States. By using the App, you represent that you\n    are located in the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the App. If you are under 18, you may only use the App if your\n    parent or legal guardian has reviewed and agreed to these Terms on your behalf and provides ongoing supervision\n    of your use.\nrestricted_uses:\n- summary: Personal\
  \ non-commercial use\n  text: You are granted a limited, non-exclusive, non-transferable, revocable license to use the App solely for\n    personal, non-commercial purposes in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the App.\n"
source_yaml_url: https://artifacts.apis.io/fortell/eligibility/fortell-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Fortell's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Hearing Aids
- Health Tech
- Audio
---
