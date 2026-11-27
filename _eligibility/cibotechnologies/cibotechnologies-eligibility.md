---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: in the United States and Canada (other than the Province of Quebec)
  entity_types:
  - text: If you access or use the Services on behalf of a company, corporation, partnership or other entity then “you” includes you and that entity
    type: business
  minimum_age:
    text: you represent and warrant to us that you are of legal age, and fully capable and competent, to enter into a legally binding agreement with CIBO
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials provided by CIBO hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
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
name: Cibotechnologies
provenance_date: '2026-11-09'
provider_name: Cibotechnologies
provider_slug: cibotechnologies
slug: cibotechnologies-eligibility
source_date: '2026-11-09'
source_filename: cibotechnologies-eligibility.yml
source_heading: Eligibility
source_page: https://www.cibotechnologies.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cibotechnologies\naid: cibotechnologies\nurl: https://www.cibotechnologies.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: in the United States and Canada (other than the Province of Quebec)\nentity_types:\n- type: business\n  text: If you access or use the Services on behalf of a company, corporation, partnership or other entity then\n    “you” includes you and that entity\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials\n    provided\
  \ by CIBO hereunder, to any country for which the United States or any other relevant jurisdiction requires\n    any export license\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent and warrant to us that you are of legal age, and fully capable and competent, to enter into\n    a legally binding agreement with CIBO\n"
source_yaml_url: https://artifacts.apis.io/cibotechnologies/eligibility/cibotechnologies-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cibotechnologies's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Agriculture
- Sustainability
- Data
---
