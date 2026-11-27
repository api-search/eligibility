---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The GetYourGuide Platform is available to users worldwide.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal use only
    text: The GetYourGuide Platform is provided for your personal, non-commercial use only.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to impose conditions on the use of the GetYourGuide Platform, including access to certain features, based on factors such as payment history or providing documentation (e.g., identity verification, payment receipts).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GetYourGuide
provenance_date: '2026-11-09'
provider_name: GetYourGuide
provider_slug: getyourguide
slug: getyourguide-eligibility
source_date: '2026-11-09'
source_filename: getyourguide-eligibility.yml
source_heading: Eligibility
source_page: https://www.getyourguide.com/c/general-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GetYourGuide\naid: getyourguide\nurl: https://www.getyourguide.com/c/general-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The GetYourGuide Platform is available to users worldwide.\nentity_types: []\nrestricted_uses:\n- summary: Personal use only\n  text: The GetYourGuide Platform is provided for your personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to impose conditions on the use of the GetYourGuide Platform, including access to certain\n    features, based\
  \ on factors such as payment history or providing documentation (e.g., identity verification,\n    payment receipts).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getyourguide/eligibility/getyourguide-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from GetYourGuide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Tourism
- Tours and Activities
- Marketplace
- Booking
- Experience
- Affiliates
- Partner API
- E-Commerce
---
