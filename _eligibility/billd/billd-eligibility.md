---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide this Website for use only by persons located in the United States.
  entity_types:
  - text: The Website is offered and available to users who are eighteen (18) years of age or older and reside in the United States or any of its territories.
    type: individual
  minimum_age:
    text: eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: access or use for any commercial purposes any part of the Website or any services or materials available through the Website
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
name: Billd
provenance_date: '2026-11-09'
provider_name: Billd
provider_slug: billd
slug: billd-eligibility
source_date: '2026-11-09'
source_filename: billd-eligibility.yml
source_heading: Eligibility
source_page: https://billd.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Billd\naid: billd\nurl: https://billd.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide this Website for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: The Website is offered and available to users who are eighteen (18) years of age or older and reside in\n    the United States or any of its territories.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: access or use for any commercial purposes any part of the Website or any services or materials available\n    through the Website\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/billd/eligibility/billd-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Billd's own page on 2026-11-09.
synthetic: false
tags:
- Construction
- Financing
- Subcontractors
- Working Capital
- Billd
---
