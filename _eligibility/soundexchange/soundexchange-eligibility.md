---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under the age of eighteen (18), you represent that you are either an emancipated minor, or have obtained the legal consent of your parent or legal guardian to enter into this Agreement or use these Sites
    value: '18'
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
name: SoundExchange
provenance_date: '2026-11-10'
provider_name: SoundExchange
provider_slug: soundexchange
slug: soundexchange-eligibility
source_date: '2026-11-10'
source_filename: soundexchange-eligibility.yml
source_heading: Eligibility
source_page: https://www.soundexchange.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SoundExchange\naid: soundexchange\nurl: https://www.soundexchange.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under the age of eighteen (18), you represent that you are either an emancipated minor, or have\n    obtained the legal consent of your parent or legal guardian to enter into this Agreement or use these Sites\n"
source_yaml_url: https://artifacts.apis.io/soundexchange/eligibility/soundexchange-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from SoundExchange's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Non-Profit
- Royalties
- Music
- Digital
- Rights
---
