---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Access to and use of the Site or the Services is limited exclusively to users located in States within the United States where the Services are available.
  entity_types:
  - text: In order to access the Site and the Services, you represent and warrant that you are older than 18 years old.
    type: individual
  minimum_age:
    text: In order to access the Site and the Services, you represent and warrant that you are older than 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful use or jurisdictions where services are not offered
    text: Accessing the Site or Services from jurisdictions where content is illegal, or where we do not offer Services, is prohibited.
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
name: Carbon Health
provenance_date: '2026-11-09'
provider_name: Carbon Health
provider_slug: carbon-health
slug: carbon-health-eligibility
source_date: '2026-11-09'
source_filename: carbon-health-eligibility.yml
source_heading: Eligibility
source_page: https://carbonhealth.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Carbon Health\naid: carbon-health\nurl: https://carbonhealth.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Access to and use of the Site or the Services is limited exclusively to users located in States within the\n    United States where the Services are available.\nentity_types:\n- type: individual\n  text: In order to access the Site and the Services, you represent and warrant that you are older than 18 years\n    old.\nrestricted_uses:\n- summary: Unlawful use or jurisdictions where services are not offered\n  text: Accessing the Site or Services from\
  \ jurisdictions where content is illegal, or where we do not offer Services,\n    is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to access the Site and the Services, you represent and warrant that you are older than 18 years\n    old.\n"
source_yaml_url: https://artifacts.apis.io/carbon-health/eligibility/carbon-health-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Carbon Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Urgent Care
- Primary Care
- Digital Health
- Clinical Research
---
