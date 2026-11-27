---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by us from our facilities in the United Kingdom. We make no representations that the Services are appropriate or available for use in all countries.
  entity_types:
  - text: Access and use of our Platform is restricted to our customers, who are generally business entities that use the Platform in the conduct of their businesses pursuant to contracts with us.
    type: business
  minimum_age:
    text: The Services are not intended for children younger than the age of 18.
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
name: Foresight
provenance_date: '2026-11-09'
provider_name: Foresight
provider_slug: foresight
slug: foresight-eligibility
source_date: '2026-11-09'
source_filename: foresight-eligibility.yml
source_heading: Eligibility
source_page: https://www.foresight.works/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Foresight\naid: foresight\nurl: https://www.foresight.works/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by us from our facilities in the United Kingdom. We make no representations\n    that the Services are appropriate or available for use in all countries.\nentity_types:\n- type: business\n  text: Access and use of our Platform is restricted to our customers, who are generally business entities that\n    use the Platform in the conduct of their businesses pursuant to contracts with us.\nrestricted_uses: []\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are not intended for children younger than the age of 18.\n"
source_yaml_url: https://artifacts.apis.io/foresight/eligibility/foresight-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Foresight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Infrastructure
- Project Management
- Predictive Analytics
- Data Center
- Software-as-a-Service
---
