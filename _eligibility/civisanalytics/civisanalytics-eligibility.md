---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: THE SITE IS NOT FOR PERSONS UNDER THE AGE OF 13.
    value: '13'
  restricted_uses:
  - summary: Private, non-commercial use only
    text: Any use by User of any of the Company Materials other than for private, non-commercial use is strictly prohibited.
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
name: Civisanalytics
provenance_date: '2026-11-09'
provider_name: Civisanalytics
provider_slug: civisanalytics
slug: civisanalytics-eligibility
source_date: '2026-11-09'
source_filename: civisanalytics-eligibility.yml
source_heading: Eligibility
source_page: https://www.civisanalytics.com/legal-pages/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Civisanalytics\naid: civisanalytics\nurl: https://www.civisanalytics.com/legal-pages/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Private, non-commercial use only\n  text: Any use by User of any of the Company Materials other than for private, non-commercial use is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: THE SITE IS NOT FOR PERSONS UNDER THE AGE OF 13.\n"
source_yaml_url: https://artifacts.apis.io/civisanalytics/eligibility/civisanalytics-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Civisanalytics's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Artificial Intelligence
- Data Platform
- Non-Profit
- Government
---
