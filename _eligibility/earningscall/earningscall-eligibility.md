---
api_specs:
- filename: earningscall-openapi-generated.yml
  format: yaml
  label: EarningsCall API
  slug: earningscall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/earningscall/openapi/_ae-authored/earningscall-openapi-generated.yml
- filename: earningscall-audio-api-openapi.yml
  format: yaml
  label: EarningsCall Audio API
  slug: earningscall-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/earningscall/openapi/earningscall-audio-api-openapi.yml
- filename: earningscall-calendar-api-openapi.yml
  format: yaml
  label: EarningsCall Calendar API
  slug: earningscall-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/earningscall/openapi/earningscall-calendar-api-openapi.yml
- filename: earningscall-events-api-openapi.yml
  format: yaml
  label: EarningsCall Events API
  slug: earningscall-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/earningscall/openapi/earningscall-events-api-openapi.yml
- filename: earningscall-live-api-openapi.yml
  format: yaml
  label: EarningsCall Live API
  slug: earningscall-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/earningscall/openapi/earningscall-live-api-openapi.yml
- filename: earningscall-slides-api-openapi.yml
  format: yaml
  label: EarningsCall Slides API
  slug: earningscall-slides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/earningscall/openapi/earningscall-slides-api-openapi.yml
- filename: earningscall-symbols-api-openapi.yml
  format: yaml
  label: EarningsCall Symbols API
  slug: earningscall-symbols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/earningscall/openapi/earningscall-symbols-api-openapi.yml
- filename: earningscall-transcript-api-openapi.yml
  format: yaml
  label: EarningsCall Transcript API
  slug: earningscall-transcript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/earningscall/openapi/earningscall-transcript-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For users who select an Individual plan, the API is intended for personal, non-commercial use only.
    type: individual
  - text: We offer dedicated Commercial API plans for businesses, academic institutions, research organizations, and professional users
    type: business
  minimum_age:
    text: We do not intentionally collect Personal Information from people who have not yet reached the age of majority in their jurisdiction.
    value: age of majority
  restricted_uses:
  - summary: No HFT or automated trading without licence
    text: Use the data in high-frequency trading (HFT) systems or automated trading strategies without a separate licensing agreement.
  - summary: Individual plans non-commercial only
    text: the API is intended for personal, non-commercial use only.
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
name: EarningsCall
provenance_date: '2026-11-09'
provider_name: EarningsCall
provider_slug: earningscall
slug: earningscall-eligibility
source_date: '2026-11-09'
source_filename: earningscall-eligibility.yml
source_heading: Eligibility
source_page: https://earningscall.biz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EarningsCall\naid: earningscall\nurl: https://earningscall.biz/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: For users who select an Individual plan, the API is intended for personal, non-commercial use only.\n- type: business\n  text: We offer dedicated Commercial API plans for businesses, academic institutions, research organizations, and\n    professional users\nrestricted_uses:\n- summary: No HFT or automated trading without licence\n  text: Use the data in high-frequency trading (HFT) systems or automated trading strategies\
  \ without a separate\n    licensing agreement.\n- summary: Individual plans non-commercial only\n  text: the API is intended for personal, non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: We do not intentionally collect Personal Information from people who have not yet reached the age of majority\n    in their jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/earningscall/eligibility/earningscall-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from EarningsCall's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Data
- Earnings
---
