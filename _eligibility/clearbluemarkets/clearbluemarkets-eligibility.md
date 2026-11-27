---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By agreeing to the Terms, you represent and warrant that you are at least the age of majority in your state or province of residence and are legally capable of entering into a binding contract.
    value: age of majority
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
name: Clearbluemarkets
provenance_date: '2026-11-09'
provider_name: Clearbluemarkets
provider_slug: clearbluemarkets
slug: clearbluemarkets-eligibility
source_date: '2026-11-09'
source_filename: clearbluemarkets-eligibility.yml
source_heading: Eligibility
source_page: https://www.clearbluemarkets.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clearbluemarkets\naid: clearbluemarkets\nurl: https://www.clearbluemarkets.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: By agreeing to the Terms, you represent and warrant that you are at least the age of majority in your state\n    or province of residence and are legally capable of entering into a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/clearbluemarkets/eligibility/clearbluemarkets-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Clearbluemarkets's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Carbon Markets
- Analytics
- Advisory
- Clean Energy
---
