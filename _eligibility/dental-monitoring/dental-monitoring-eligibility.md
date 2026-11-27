---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Product availability, claims and regulatory status may differ across countries depending on local regulations.
  entity_types:
  - text: It is also used by patients under the mandatory supervision of Healthcare Professionals (HCPs).
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use under HCP guidance
    text: Refer to your HCP and/or the Instructions for Use before use.
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
name: Dental Monitoring
provenance_date: '2026-11-09'
provider_name: Dental Monitoring
provider_slug: dental-monitoring
slug: dental-monitoring-eligibility
source_date: '2026-11-09'
source_filename: dental-monitoring-eligibility.yml
source_heading: Eligibility
source_page: https://dentalmonitoring.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dental Monitoring\naid: dental-monitoring\nurl: https://dentalmonitoring.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Product availability, claims and regulatory status may differ across countries depending on local regulations.\nentity_types:\n- type: other\n  text: It is also used by patients under the mandatory supervision of Healthcare Professionals (HCPs).\nrestricted_uses:\n- summary: Use under HCP guidance\n  text: Refer to your HCP and/or the Instructions for Use before use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dental-monitoring/eligibility/dental-monitoring-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Dental Monitoring's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Dental
- Artificial Intelligence
- Healthcare
- Orthodontics
---
