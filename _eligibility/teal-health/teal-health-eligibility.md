---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Platform is limited exclusively to users located in states within the United States where the Platform is available. Services are not available to users located outside the United States.
  entity_types:
  - text: In order to access the Platform and the Services, you represent and warrant that you are 18 years old or older.
    type: individual
  minimum_age:
    text: you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Accessing from unavailable jurisdictions
    text: Accessing the Platform from jurisdictions where content is illegal, or where we do not offer the Platform, is prohibited.
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
name: Teal Health
provenance_date: '2026-11-10'
provider_name: Teal Health
provider_slug: teal-health
slug: teal-health-eligibility
source_date: '2026-11-10'
source_filename: teal-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.getteal.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Teal Health\naid: teal-health\nurl: https://www.getteal.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: In order to access the Platform and the Services, you represent and warrant that you are 18 years old or\n    older.\nrestricted_uses:\n- summary: Accessing from unavailable jurisdictions\n  text: Accessing\
  \ the Platform from jurisdictions where content is illegal, or where we do not offer the Platform,\n    is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you represent and warrant that you are 18 years old or older.\n"
source_yaml_url: https://artifacts.apis.io/teal-health/eligibility/teal-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Teal Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Women's Health
- Cervical Cancer Screening
- HPV Testing
- Diagnostics
- Femtech
---
