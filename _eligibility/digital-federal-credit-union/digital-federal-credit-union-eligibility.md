---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is provided for your personal and non-commercial use, unless otherwise specified in writing.
    type: individual
  minimum_age:
    text: BY ACCESSING, VISITING, BROWSING, USING, OR ATTEMPTING TO INTERACT WITH OR USE ANY PART OF THIS SITE, YOU AGREE THAT YOU HAVE READ, UNDERSTAND, AND AGREE TO BE BOUND BY THIS AGREEMENT AND THAT YOU ARE AT LEAST 18 YEARS OF AGE.
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: You may not use the Site for any other purpose, including any commercial purpose, without our prior express written permission.
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
name: DCU (Digital Federal Credit Union)
provenance_date: '2026-11-09'
provider_name: DCU (Digital Federal Credit Union)
provider_slug: digital-federal-credit-union
slug: digital-federal-credit-union-eligibility
source_date: '2026-11-09'
source_filename: digital-federal-credit-union-eligibility.yml
source_heading: Eligibility
source_page: https://www.dcu.org/dcu-support-center/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DCU (Digital Federal Credit Union)\naid: digital-federal-credit-union\nurl: https://www.dcu.org/dcu-support-center/terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is provided for your personal and non-commercial use, unless otherwise specified in writing.\nrestricted_uses:\n- summary: Commercial use\n  text: You may not use the Site for any other purpose, including any commercial purpose, without our prior express\n    written permission.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: BY ACCESSING, VISITING, BROWSING, USING, OR ATTEMPTING TO INTERACT WITH OR USE ANY PART OF THIS SITE, YOU\n    AGREE THAT YOU HAVE READ, UNDERSTAND, AND AGREE TO BE BOUND BY THIS AGREEMENT AND THAT YOU ARE AT LEAST 18 YEARS\n    OF AGE.\n"
source_yaml_url: https://artifacts.apis.io/digital-federal-credit-union/eligibility/digital-federal-credit-union-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from DCU (Digital Federal Credit Union)'s own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- United States
- Credit Union
- Consumer Banking
- Open Finance
---
