---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - MY
    text: Smart EV charging for homes, condos, businesses and the public across Malaysia.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Legal and proper use only
    text: You agree to use the services only for purposes that are legal, proper and in accordance with the terms herein.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may verify and authorise your credit or debit card details when you first register with us as well as when you use the Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Chargesini
provenance_date: '2026-11-09'
provider_name: Chargesini
provider_slug: chargesini
slug: chargesini-eligibility
source_date: '2026-11-09'
source_filename: chargesini-eligibility.yml
source_heading: Eligibility
source_page: https://www.chargesini.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chargesini\naid: chargesini\nurl: https://www.chargesini.com/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - MY\n  excluded: []\n  text: Smart EV charging for homes, condos, businesses and the public across Malaysia.\nentity_types: []\nrestricted_uses:\n- summary: Legal and proper use only\n  text: You agree to use the services only for purposes that are legal, proper and in accordance with the terms\n    herein.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may verify and authorise your credit or debit card details when you first register with us\
  \ as well as\n    when you use the Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chargesini/eligibility/chargesini-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Chargesini's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EV Charging
- Malaysia
- Sustainability
- Mobile App
---
