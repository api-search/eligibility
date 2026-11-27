---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: Services on the Platform would be available to only select geographies in India.
  entity_types:
  - text: Persons who are “incompetent to contract” within the meaning of the Indian Contract Act, 1872 including minors, un-discharged insolvents etc. are not eligible to use the Platform.
    type: individual
  - text: if you are a minor, i.e. under the age of 18 years and over the age of 3 years, you may use the Platform under the supervision of a parent or legal guardian
    type: individual
  minimum_age:
    text: if you are a minor, i.e. under the age of 18 years and over the age of 3 years, you may use the Platform under the supervision of a parent or legal guardian
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: solely for your personal, non -commercial use.
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
name: PlanetSpark
provenance_date: '2026-11-10'
provider_name: PlanetSpark
provider_slug: planetspark
slug: planetspark-eligibility
source_date: '2026-11-10'
source_filename: planetspark-eligibility.yml
source_heading: Eligibility
source_page: https://www.planetspark.in/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PlanetSpark\naid: planetspark\nurl: https://www.planetspark.in/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: Services on the Platform would be available to only select geographies in India.\nentity_types:\n- type: individual\n  text: Persons who are “incompetent to contract” within the meaning of the Indian Contract Act, 1872 including\n    minors, un-discharged insolvents etc. are not eligible to use the Platform.\n- type: individual\n  text: if you are a minor, i.e. under the age of 18 years and over the age of 3 years, you may use the Platform\n    under the supervision\
  \ of a parent or legal guardian\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: solely for your personal, non -commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are a minor, i.e. under the age of 18 years and over the age of 3 years, you may use the Platform\n    under the supervision of a parent or legal guardian\n"
source_yaml_url: https://artifacts.apis.io/planetspark/eligibility/planetspark-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from PlanetSpark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- E-Learning
- Tutoring
- Public Speaking
- English Language
- Mathematics
- Consumer
- India
---
