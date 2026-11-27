---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are not available to users located outside the United States.
  entity_types:
  - text: The Site and Services are only for users of the age of 18 or older.
    type: individual
  minimum_age:
    text: The Site and Services are only for users of the age of 18 or older.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited jurisdictions
    text: Accessing the Site or Services from jurisdictions where the content is illegal or penalized, or where we do not offer Services, is prohibited.
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
name: AmplifyMD
provenance_date: '2026-11-09'
provider_name: AmplifyMD
provider_slug: amplifymd
slug: amplifymd-eligibility
source_date: '2026-11-09'
source_filename: amplifymd-eligibility.yml
source_heading: Eligibility
source_page: https://amplifymd.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AmplifyMD\naid: amplifymd\nurl: https://amplifymd.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are not available to users located outside the United States.\nentity_types:\n- type: individual\n  text: The Site and Services are only for users of the age of 18 or older.\nrestricted_uses:\n- summary: Unlawful or prohibited jurisdictions\n  text: Accessing the Site or Services from jurisdictions where the content is illegal or penalized, or where we\n    do not offer Services, is prohibited.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and Services are only for users of the age of 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/amplifymd/eligibility/amplifymd-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AmplifyMD's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Telehealth
- Virtual Care
- EHR Integration
---
