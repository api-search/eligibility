---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Gyroscope makes no representation that the Content or the Services are appropriate or available for use in other locations.
  entity_types:
  - text: You must be at least 18 to register, access, or use Gyroscope.
    type: individual
  - text: If you access or use the Services on behalf of a company or other entity, you represent that you have authority to bind such entity and its affiliates to these Terms
    type: business
  minimum_age:
    text: By using the Services, you represent and warrant that you are 18 or older
    value: '18'
  restricted_uses:
  - summary: Illegal territories
    text: Access to or use of the Content or the Services from territories where such access or use is illegal is prohibited.
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
name: Gyroscope
provenance_date: '2026-11-09'
provider_name: Gyroscope
provider_slug: gyroscope
slug: gyroscope-eligibility
source_date: '2026-11-09'
source_filename: gyroscope-eligibility.yml
source_heading: Eligibility
source_page: https://gyrosco.pe/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gyroscope\naid: gyroscope\nurl: https://gyrosco.pe/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Gyroscope makes no representation that the Content or the Services are appropriate or available for use\n    in other locations.\nentity_types:\n- type: individual\n  text: You must be at least 18 to register, access, or use Gyroscope.\n- type: business\n  text: If you access or use the Services on behalf of a company or other entity, you represent that you have authority\n    to bind such entity and its affiliates to these Terms\nrestricted_uses:\n- summary: Illegal territories\n\
  \  text: Access to or use of the Content or the Services from territories where such access or use is illegal is\n    prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By using the Services, you represent and warrant that you are 18 or older\n"
source_yaml_url: https://artifacts.apis.io/gyroscope/eligibility/gyroscope-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Gyroscope's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Tracking
- Artificial Intelligence
- Wellness
---
