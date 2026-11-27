---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Your use of the Services is limited to the country or jurisdiction where you established your User Account and to areas where Signos offers the Services.
  entity_types:
  - text: The Site, the App, and the Services are offered only to users eighteen (18) years of age or older, or otherwise the age of majority in each user's respective jurisdiction
    type: individual
  minimum_age:
    text: offered only to users eighteen (18) years of age or older, or otherwise the age of majority in each user's respective jurisdiction
    value: '18'
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
name: Signos
provenance_date: '2026-11-10'
provider_name: Signos
provider_slug: signos
slug: signos-eligibility
source_date: '2026-11-10'
source_filename: signos-eligibility.yml
source_heading: Eligibility
source_page: https://www.signos.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Signos\naid: signos\nurl: https://www.signos.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Your use of the Services is limited to the country or jurisdiction where you established your User Account\n    and to areas where Signos offers the Services.\nentity_types:\n- type: individual\n  text: The Site, the App, and the Services are offered only to users eighteen (18) years of age or older, or otherwise\n    the age of majority in each user's respective jurisdiction\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: offered only to users eighteen (18) years of age or older, or otherwise the age of majority in each user's\n    respective jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/signos/eligibility/signos-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Signos's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Health
- Digital Health
- Metabolic Health
- Continuous Glucose Monitoring
- Weight Management
- Wellness
---
