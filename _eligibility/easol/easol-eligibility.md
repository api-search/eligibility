---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: availability can vary by Your specific plan or jurisdiction.
  entity_types:
  - text: If Your company is registered in the United Kingdom or Europe then this section applies to You
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No unlawful or deceptive products
    text: 'You must not sell, advertise, or promote any product or service that is or would be reasonably considered: fraudulent, counterfeit, or stolen; abusive, deceptive, or unlawful;'
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
name: Easol
provenance_date: '2026-11-09'
provider_name: Easol
provider_slug: easol
slug: easol-eligibility
source_date: '2026-11-09'
source_filename: easol-eligibility.yml
source_heading: Eligibility
source_page: https://easol.com/creator-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Easol\naid: easol\nurl: https://easol.com/creator-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: availability can vary by Your specific plan or jurisdiction.\nentity_types:\n- type: business\n  text: If Your company is registered in the United Kingdom or Europe then this section applies to You\nrestricted_uses:\n- summary: No unlawful or deceptive products\n  text: 'You must not sell, advertise, or promote any product or service that is or would be reasonably considered:\n    fraudulent, counterfeit, or stolen; abusive, deceptive, or unlawful;'\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/easol/eligibility/easol-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Easol's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Experience Commerce
- Ticketing
- Booking
- Payments
- Event
- Travel
- CRM
---
