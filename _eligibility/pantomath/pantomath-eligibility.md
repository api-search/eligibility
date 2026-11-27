---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under the age of eighteen (18), then you are not permitted to register as a user
    type: individual
  - text: If you are using our Website on behalf of a business, that business accepts these terms.
    type: business
  minimum_age:
    text: If you are under the age of eighteen (18), then you are not permitted to register as a user, sign up for any promotional messages, or otherwise provide us any personal information.
    value: '18'
  restricted_uses:
  - summary: Violating export laws
    text: Violate U.S. export laws, including, without limitation, violations of the Export Administration Act and the Export Administration Regulations administered by the Department of Commerce
  - summary: Driving distraction
    text: You understand and agree that your use of the Services and/or Service Content while operating a motor vehicle (or during any other activity that requires your attention) may be distracting, dangerous, or prohibited by law.
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
name: Pantomath
provenance_date: '2026-11-10'
provider_name: Pantomath
provider_slug: pantomath
slug: pantomath-eligibility
source_date: '2026-11-10'
source_filename: pantomath-eligibility.yml
source_heading: Eligibility
source_page: https://www.pantomath.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pantomath\naid: pantomath\nurl: https://www.pantomath.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under the age of eighteen (18), then you are not permitted to register as a user\n- type: business\n  text: If you are using our Website on behalf of a business, that business accepts these terms.\nrestricted_uses:\n- summary: Violating export laws\n  text: Violate U.S. export laws, including, without limitation, violations of the Export Administration Act and\n    the Export Administration Regulations administered\
  \ by the Department of Commerce\n- summary: Driving distraction\n  text: You understand and agree that your use of the Services and/or Service Content while operating a motor vehicle\n    (or during any other activity that requires your attention) may be distracting, dangerous, or prohibited by\n    law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under the age of eighteen (18), then you are not permitted to register as a user, sign up for\n    any promotional messages, or otherwise provide us any personal information.\n"
source_yaml_url: https://artifacts.apis.io/pantomath/eligibility/pantomath-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Pantomath's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Observability
- Data Operations
- Data Pipeline Monitoring
- Data Lineage
- Data Quality
- Data Reliability
- Analytics
---
