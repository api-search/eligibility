---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Our Services are only intended for use in the United States of America
  entity_types:
  - text: If you use our Services in connection with an organization, such as your employer, you must use it in compliance with your organization's terms and policies.
    type: business
  minimum_age:
    text: may not be used by anyone under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Not for life safety or critical purposes
    text: YOU AGREE THAT YOU WILL NOT RELY ON THE SERVICES FOR ANY LIFE SAFETY OR CRITICAL PURPOSES.
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
name: Roby
provenance_date: '2026-11-10'
provider_name: Roby
provider_slug: roby
slug: roby-eligibility
source_date: '2026-11-10'
source_filename: roby-eligibility.yml
source_heading: Eligibility
source_page: https://tellroby.com/terms-of-service.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Roby\naid: roby\nurl: https://tellroby.com/terms-of-service.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Our Services are only intended for use in the United States of America\nentity_types:\n- type: business\n  text: If you use our Services in connection with an organization, such as your employer, you must use it in compliance\n    with your organization's terms and policies.\nrestricted_uses:\n- summary: Not for life safety or critical purposes\n  text: YOU AGREE THAT YOU WILL NOT RELY ON THE SERVICES FOR ANY LIFE SAFETY OR CRITICAL PURPOSES.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: may not be used by anyone under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/roby/eligibility/roby-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Roby's own page on 2026-11-10.
synthetic: false
tags:
- Company
- HVAC
- Building Management
- Energy Efficiency
- Automation
- Facilities
- Sustainability
- Workplace
---
