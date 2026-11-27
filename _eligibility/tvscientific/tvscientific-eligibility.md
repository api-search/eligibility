---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CH
    - GB
    served: []
    text: Company acknowledges that tvScientific does not currently offer its Services in, or support user accounts from, Switzerland, the UK or countries in the European Economic Area.
  entity_types:
  - text: the entity that executes a document that links to this Agreement or that accepts this Agreement electronically (“Company”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No non-advertising uses
    text: Company shall not use the Platform or any tvScientific Data for any non-advertising purposes, including without limitation decisions relating to eligibility for, or pricing of, employment, credit, health care, insurance, housing, or education.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company may be subject to a credit check prior to first using the Services and from time to time.
excluded_countries:
- CH
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tvscientific
provenance_date: '2026-11-10'
provider_name: Tvscientific
provider_slug: tvscientific
slug: tvscientific-eligibility
source_date: '2026-11-10'
source_filename: tvscientific-eligibility.yml
source_heading: Eligibility
source_page: https://www.tvscientific.com/platform-master-agreement-demand/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tvscientific\naid: tvscientific\nurl: https://www.tvscientific.com/platform-master-agreement-demand/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CH\n  - GB\n  text: Company acknowledges that tvScientific does not currently offer its Services in, or support user accounts\n    from, Switzerland, the UK or countries in the European Economic Area.\nentity_types:\n- type: business\n  text: the entity that executes a document that links to this Agreement or that accepts this Agreement electronically\n    (“Company”)\nrestricted_uses:\n- summary: No non-advertising uses\n  text: Company shall\
  \ not use the Platform or any tvScientific Data for any non-advertising purposes, including\n    without limitation decisions relating to eligibility for, or pricing of, employment, credit, health care, insurance,\n    housing, or education.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Company may be subject to a credit check prior to first using the Services and from time to time.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tvscientific/eligibility/tvscientific-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Tvscientific's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Connected TV
- CTV
- Streaming
- Performance Marketing
- AdTech
- Measurements
- Campaign Management
- Real-Time Bidding
- Attribution
---
