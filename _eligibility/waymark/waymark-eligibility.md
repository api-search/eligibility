---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Waymark does not knowingly collect, either online or offline, personal information from persons under the age of thirteen. If you are under 18, you may use the Website only with permission of a parent or guardian.
    value: '13'
  restricted_uses:
  - summary: Violating laws or accessing others' health information
    text: Attempt to gain unauthorized access to another individual’s personal information, non-personal information, or protected health information; and Violate any applicable laws or regulations.
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
name: Waymark
provenance_date: '2026-11-10'
provider_name: Waymark
provider_slug: waymark
slug: waymark-eligibility
source_date: '2026-11-10'
source_filename: waymark-eligibility.yml
source_heading: Eligibility
source_page: https://www.waymarkcare.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Waymark\naid: waymark\nurl: https://www.waymarkcare.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Violating laws or accessing others' health information\n  text: Attempt to gain unauthorized access to another individual’s personal information, non-personal information,\n    or protected health information; and Violate any applicable laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Waymark does not knowingly collect, either online\
  \ or offline, personal information from persons under the\n    age of thirteen. If you are under 18, you may use the Website only with permission of a parent or guardian.\n"
source_yaml_url: https://artifacts.apis.io/waymark/eligibility/waymark-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Waymark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Medicaid
- Community Health
- Value-Based Care
- Care Coordination
- Population Health
---
