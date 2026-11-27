---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Import/export control compliance
    text: You agree to comply with all applicable laws and regulations regarding your use of the Site and the import and export of this information.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Certain features of the Site may require the opening of a user account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vaisala
provenance_date: '2026-11-10'
provider_name: Vaisala
provider_slug: vaisala
slug: vaisala-eligibility
source_date: '2026-11-10'
source_filename: vaisala-eligibility.yml
source_heading: Eligibility
source_page: https://www.vaisala.com/en/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vaisala\naid: vaisala\nurl: https://www.vaisala.com/en/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Import/export control compliance\n  text: You agree to comply with all applicable laws and regulations regarding your use of the Site and the import\n    and export of this information.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Certain features of the Site may require the opening of a user account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vaisala/eligibility/vaisala-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Vaisala's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Weather
- Climate
- Sensors
- Industrial
---
