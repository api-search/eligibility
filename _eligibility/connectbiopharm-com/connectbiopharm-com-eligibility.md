---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that our Site is appropriate or available for use outside the United States.
  minimum_age:
    text: Our Site is not intended for users under the age of 18.
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: THE INFORMATION PROVIDED ON OUR SITE IS NOT INTENDED TO SERVE AS MEDICAL OR OTHER PROFESSIONAL ADVICE
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
name: connectbiopharm
provenance_date: '2026-11-09'
provider_name: connectbiopharm
provider_slug: connectbiopharm-com
slug: connectbiopharm-com-eligibility
source_date: '2026-11-09'
source_filename: connectbiopharm-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.connectbiopharma.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: connectbiopharm\naid: connectbiopharm-com\nurl: https://www.connectbiopharma.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that our Site is appropriate or available for use outside the United States.\nentity_types: []\nrestricted_uses:\n- summary: Not medical advice\n  text: THE INFORMATION PROVIDED ON OUR SITE IS NOT INTENDED TO SERVE AS MEDICAL OR OTHER PROFESSIONAL ADVICE\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our Site is not intended for users\
  \ under the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/connectbiopharm-com/eligibility/connectbiopharm-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from connectbiopharm's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Biopharma
- Clinical Stage
- Asthma
- COPD
- Inflammatory Diseases
---
