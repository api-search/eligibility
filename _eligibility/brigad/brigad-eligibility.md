---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: If your country of residence or establishment is in the United Kingdom, the General conditions of use apply to you.
  entity_types:
  - text: Any legal person seeking a one-time need for Services may apply for registration via the Site or Application
    type: business
  - text: Anyone can apply for registration via the Site or Application, provided they provide the required information
    type: individual
  minimum_age:
    text: be of age and have the ability to contract with Brigad, in accordance with the laws of the country in which they operate
    value: of age
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Brigad reserves the right to refuse any application for registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Brigad
provenance_date: '2026-11-09'
provider_name: Brigad
provider_slug: brigad
slug: brigad-eligibility
source_date: '2026-11-09'
source_filename: brigad-eligibility.yml
source_heading: Eligibility
source_page: https://www.brigad.co/en-gb/legal/general-conditions-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Brigad\naid: brigad\nurl: https://www.brigad.co/en-gb/legal/general-conditions-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: If your country of residence or establishment is in the United Kingdom, the General conditions of use apply\n    to you.\nentity_types:\n- type: business\n  text: Any legal person seeking a one-time need for Services may apply for registration via the Site or Application\n- type: individual\n  text: Anyone can apply for registration via the Site or Application, provided they provide the required information\nrestricted_uses:\
  \ []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Brigad reserves the right to refuse any application for registration.\nminimum_age:\n  value: of age\n  text: be of age and have the ability to contract with Brigad, in accordance with the laws of the country in which\n    they operate\n"
source_yaml_url: https://artifacts.apis.io/brigad/eligibility/brigad-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Brigad's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Staffing
- Marketplace
- Hospitality
- Healthcare
- Gig Economy
- Freelance
- Workforce
---
