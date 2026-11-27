---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer represents, warrants, and covenants that Customer is not (a) located in, or a resident or a national of, any country subject to a U.S. government embargo or other restriction, or that has been designated by the U.S. government as a “terrorist supporting” country
  entity_types:
  - text: it is a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized to do business pursuant to applicable law
    type: individual
  minimum_age:
    text: it is a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized to do business pursuant to applicable law
    value: '18'
  restricted_uses:
  - summary: No personal, family or household use
    text: use Kevala's Platform for any personal, family or household use or otherwise for the benefit of any individual consumer.
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
name: Kevala
provenance_date: '2026-11-09'
provider_name: Kevala
provider_slug: kevala
slug: kevala-eligibility
source_date: '2026-11-09'
source_filename: kevala-eligibility.yml
source_heading: Eligibility
source_page: https://www.kevala.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kevala\naid: kevala\nurl: https://www.kevala.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer represents, warrants, and covenants that Customer is not (a) located in, or a resident or a national\n    of, any country subject to a U.S. government embargo or other restriction, or that has been designated by the\n    U.S. government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: it is a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized\n    to do business pursuant to applicable\
  \ law\nrestricted_uses:\n- summary: No personal, family or household use\n  text: use Kevala's Platform for any personal, family or household use or otherwise for the benefit of any individual\n    consumer.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: it is a corporation, the sole proprietorship of an individual 18 years or older, or another entity authorized\n    to do business pursuant to applicable law\n"
source_yaml_url: https://artifacts.apis.io/kevala/eligibility/kevala-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kevala's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Electricity
- Electric Grid
- Grid Analytics
- Distributed Energy Resources
- Utilities
- Geospatial
- Analytics
- Carbon Accounting
- Electric Vehicles
- Sustainability
---
