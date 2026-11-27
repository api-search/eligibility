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
    text: In order to access the Platform and the Services, you represent and warrant that you are 18 years old or older.
    value: '18'
  restricted_uses:
  - summary: Pregnancy
    text: Do not use the Platform if you are or think you may be pregnant.
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
name: kaiahealth
provenance_date: '2026-11-09'
provider_name: kaiahealth
provider_slug: kaiahealth
slug: kaiahealth-eligibility
source_date: '2026-11-09'
source_filename: kaiahealth-eligibility.yml
source_heading: Eligibility
source_page: https://kaiahealth.com/legal/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kaiahealth\naid: kaiahealth\nurl: https://kaiahealth.com/legal/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Platform is limited exclusively to users located in states within the United States\n    where the Platform is available. Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: In order to access the Platform and the Services, you represent and warrant that you are 18 years old or\n    older.\nrestricted_uses:\n- summary: Pregnancy\n  text: Do not use the Platform\
  \ if you are or think you may be pregnant.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to access the Platform and the Services, you represent and warrant that you are 18 years old or\n    older.\n"
source_yaml_url: https://artifacts.apis.io/kaiahealth/eligibility/kaiahealth-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from kaiahealth's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Therapeutics
- Digital Health
- Healthcare
- Musculoskeletal
- MSK
- DTx
- Physical Therapy
---
