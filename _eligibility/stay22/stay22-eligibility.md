---
api_specs:
- filename: stay22-openapi-generated.yml
  format: yaml
  label: Stay22 API
  slug: stay22-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stay22/openapi/_ae-authored/stay22-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you or the entity you represent
    type: business
  minimum_age:
    text: YOU HAVE REACHED THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION
    value: age of majority in jurisdiction
  restricted_uses:
  - summary: Direct competitors
    text: STAY22 DIRECT COMPETITORS ARE PROHIBITED FROM USING THE STAY22 PRODUCTS OR SOLUTION, EXCEPT WITH STAY22 PRIOR WRITTEN CONSENT.
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
name: Stay22
provenance_date: '2026-11-10'
provider_name: Stay22
provider_slug: stay22
slug: stay22-eligibility
source_date: '2026-11-10'
source_filename: stay22-eligibility.yml
source_heading: Eligibility
source_page: https://www.stay22.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stay22\naid: stay22\nurl: https://www.stay22.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you or the entity you represent\nrestricted_uses:\n- summary: Direct competitors\n  text: STAY22 DIRECT COMPETITORS ARE PROHIBITED FROM USING THE STAY22 PRODUCTS OR SOLUTION, EXCEPT WITH STAY22\n    PRIOR WRITTEN CONSENT.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in jurisdiction\n  text: YOU HAVE REACHED THE LEGAL AGE OF MAJORITY IN YOUR JURISDICTION\n"
source_yaml_url: https://artifacts.apis.io/stay22/eligibility/stay22-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Stay22's own page on 2026-11-10.
synthetic: false
tags:
- TravelTech
- Affiliate Marketing
- Software-as-a-Service
- Event
- Maps
---
