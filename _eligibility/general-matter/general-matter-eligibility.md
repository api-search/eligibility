---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Site is intended for visitors located within the United States. We make no representation that the Site is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 18 years old to use the Site.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Site.
    value: '18'
  restricted_uses:
  - summary: Illegal or rights-infringing use
    text: use the Site for any illegal purpose or in violation of any local, state, national, or international law;
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
name: General Matter
provenance_date: '2026-11-09'
provider_name: General Matter
provider_slug: general-matter
slug: general-matter-eligibility
source_date: '2026-11-09'
source_filename: general-matter-eligibility.yml
source_heading: Eligibility
source_page: https://generalmatter.com/privacy-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: General Matter\naid: general-matter\nurl: https://generalmatter.com/privacy-terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Site is intended for visitors located within the United States. We make no representation that the Site\n    is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site.\nrestricted_uses:\n- summary: Illegal or rights-infringing use\n  text: use the Site for any illegal purpose or in violation of any local, state, national, or international law;\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/general-matter/eligibility/general-matter-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from General Matter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Energy
- Nuclear
- Nuclear Fuel
- Uranium Enrichment
- HALEU
- Cleantech
---
