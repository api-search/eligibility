---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We accept credit and debit cards issued by U.S. banks.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No resale to dealers or resellers
    text: Allara also reserves the right, at our sole discretion, to prohibit sales to dealers or resellers.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Allara and your Provider may contact you by telephone, mail, or email to verify your information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Allara
provenance_date: '2026-11-09'
provider_name: Allara
provider_slug: allara
slug: allara-eligibility
source_date: '2026-11-09'
source_filename: allara-eligibility.yml
source_heading: Eligibility
source_page: https://www.allarahealth.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Allara\naid: allara\nurl: https://www.allarahealth.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We accept credit and debit cards issued by U.S. banks.\nentity_types: []\nrestricted_uses:\n- summary: No resale to dealers or resellers\n  text: Allara also reserves the right, at our sole discretion, to prohibit sales to dealers or resellers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Allara and your Provider may contact you by telephone, mail, or email to verify your information.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/allara/eligibility/allara-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Allara's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Women's Health
- Hormonal Health
- Digital Health
- PCOS
- Virtual Care
---
