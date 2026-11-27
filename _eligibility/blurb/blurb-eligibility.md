---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To order any Books, Wall Art, or other products, you must be at least eighteen (18) years of age or the applicable age of majority in your jurisdiction.
    type: individual
  minimum_age:
    text: you are in the U.S. and thirteen (13) years of age or older, or in the EU and sixteen (16) years of age or older
    value: '13'
  restricted_uses:
  - summary: Prohibited content categories
    text: YOU MAY NOT INCLUDE "PUBLISHED BY BLURB," "BLURB PUBLISHING" OR ANY OTHER REFERENCE THAT DIRECTLY OR INDIRECTLY SUGGESTS OR IMPLIES THAT BLURB IS THE PUBLISHER OF THE BOOK(S) THAT YOU CREATE USING THE SERVICES.
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
name: Blurb
provenance_date: '2026-11-09'
provider_name: Blurb
provider_slug: blurb
slug: blurb-eligibility
source_date: '2026-11-09'
source_filename: blurb-eligibility.yml
source_heading: Eligibility
source_page: https://www.blurb.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blurb\naid: blurb\nurl: https://www.blurb.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To order any Books, Wall Art, or other products, you must be at least eighteen (18) years of age or the\n    applicable age of majority in your jurisdiction.\nrestricted_uses:\n- summary: Prohibited content categories\n  text: YOU MAY NOT INCLUDE \"PUBLISHED BY BLURB,\" \"BLURB PUBLISHING\" OR ANY OTHER REFERENCE THAT DIRECTLY OR INDIRECTLY\n    SUGGESTS OR IMPLIES THAT BLURB IS THE PUBLISHER OF THE BOOK(S) THAT YOU CREATE USING THE\
  \ SERVICES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are in the U.S. and thirteen (13) years of age or older, or in the EU and sixteen (16) years of age\n    or older\n"
source_yaml_url: https://artifacts.apis.io/blurb/eligibility/blurb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Blurb's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Publishing
- Printing
- Print on Demand
- Books
- Self-Publishing
- Photo Books
- Fulfillment
- E-Commerce
---
