---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents and warrants that it is not on any government list of prohibited or restricted parties or located in (or a national of) a country subject to a government embargo or that has been designated by the government as a “terrorist supporting” country.
  entity_types:
  - text: If you are accessing or using the Stark Lab Services on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use in violation of law
    text: (vii) use the Stark Lab Service in violation of applicable laws (including to conduct, promote or encourage any criminal or illegal activity or enterprise)
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
name: Stark
provenance_date: '2026-11-10'
provider_name: Stark
provider_slug: stark
slug: stark-eligibility
source_date: '2026-11-10'
source_filename: stark-eligibility.yml
source_heading: Eligibility
source_page: https://www.getstark.co/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stark\naid: stark\nurl: https://www.getstark.co/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents and warrants that it is not on any government list of prohibited or restricted parties\n    or located in (or a national of) a country subject to a government embargo or that has been designated by the\n    government as a “terrorist supporting” country.\nentity_types:\n- type: business\n  text: If you are accessing or using the Stark Lab Services on behalf of your company, you represent that you are\n    authorized to accept this Agreement on behalf of your company\n\
  restricted_uses:\n- summary: No use in violation of law\n  text: (vii) use the Stark Lab Service in violation of applicable laws (including to conduct, promote or encourage\n    any criminal or illegal activity or enterprise)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stark/eligibility/stark-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Stark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Accessibility
- Compliance
- Design Tools
- Developer Tools
- WCAG
- Governance
- Software-as-a-Service
---
