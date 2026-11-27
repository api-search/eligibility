---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Materials may not be appropriate or available for use in other locations. If you use this Site outside India, you are responsible for following applicable local laws.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for emergencies
    text: USE OF OUR SERVICES IS NOT APPROPRIATE FOR EMERGENCIES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Teslon does standard checks to ensure the qualifications of the care providers on the Carenation platform including the checking of certifications from the relevant boards.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Carenation
provenance_date: '2026-11-09'
provider_name: Carenation
provider_slug: carenation
slug: carenation-eligibility
source_date: '2026-11-09'
source_filename: carenation-eligibility.yml
source_heading: Eligibility
source_page: https://carenation.in/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carenation\naid: carenation\nurl: https://carenation.in/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Materials may not be appropriate or available for use in other locations. If you use this Site outside India,\n    you are responsible for following applicable local laws.\nentity_types: []\nrestricted_uses:\n- summary: Not for emergencies\n  text: USE OF OUR SERVICES IS NOT APPROPRIATE FOR EMERGENCIES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Teslon does standard checks to ensure the qualifications of the care providers on\
  \ the Carenation platform\n    including the checking of certifications from the relevant boards.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/carenation/eligibility/carenation-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Carenation's own page on 2026-11-09.
synthetic: false
tags:
- Telehealth
- Healthcare
- Remote Care
- Digital Health
- Platform
---
