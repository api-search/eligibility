---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: One Medical services are only available in the U.S. The information provided on this website is not intended for consumers outside of the U.S.
  minimum_age:
    text: null
    value: null
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
name: One Medical *
provenance_date: '2026-11-10'
provider_name: One Medical *
provider_slug: one-medical
slug: one-medical-eligibility
source_date: '2026-11-10'
source_filename: one-medical-eligibility.yml
source_heading: Eligibility
source_page: https://www.onemedical.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: One Medical *\naid: one-medical\nurl: https://www.onemedical.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: One Medical services are only available in the U.S. The information provided on this website is not intended\n    for consumers outside of the U.S.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/one-medical/eligibility/one-medical-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from One Medical *'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Life Sciences
- Healthcare
- Primary Care
- Telehealth
- Amazon
---
