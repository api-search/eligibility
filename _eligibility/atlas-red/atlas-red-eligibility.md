---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: currently including Cuba, Iran, North Korea, Syria, and the Crimea, so-called Donetsk, and so-called Luhansk regions of Ukraine
  entity_types:
  - text: You must be at least eighteen (18) years old and able to form a binding contract to use the Service.
    type: individual
  - text: If you use the Service on behalf of an organization, you represent that you have authority to bind that organization, and "you" includes that organization.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old and able to form a binding contract to use the Service.
    value: '18'
  restricted_uses:
  - summary: No FCRA consumer report use
    text: YOU SHALL NOT USE THE SERVICE OR ANY RED ATLAS DATA, IN WHOLE OR IN PART, AS A FACTOR IN ESTABLISHING ANY PERSON'S ELIGIBILITY FOR CREDIT, INSURANCE, EMPLOYMENT, HOUSING, TENANCY, GOVERNMENT BENEFITS
  - summary: No unlawful discrimination uses
    text: or in violation of fair-housing, fair-lending, anti-discrimination, privacy, or marketing laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: RED Atlas Inc
provenance_date: '2026-11-09'
provider_name: RED Atlas Inc
provider_slug: atlas-red
slug: atlas-red-eligibility
source_date: '2026-11-09'
source_filename: atlas-red-eligibility.yml
source_heading: Eligibility
source_page: https://atlas.red/en/notices/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RED Atlas Inc\naid: atlas-red\nurl: https://atlas.red/en/notices/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: currently including Cuba, Iran, North Korea, Syria, and the Crimea, so-called Donetsk, and so-called Luhansk\n    regions of Ukraine\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old and able to form a binding contract to use the Service.\n- type: business\n  text: If you use the Service on behalf of an organization, you represent that you have authority to bind that\n    organization, and \"you\"\
  \ includes that organization.\nrestricted_uses:\n- summary: No FCRA consumer report use\n  text: YOU SHALL NOT USE THE SERVICE OR ANY RED ATLAS DATA, IN WHOLE OR IN PART, AS A FACTOR IN ESTABLISHING ANY\n    PERSON'S ELIGIBILITY FOR CREDIT, INSURANCE, EMPLOYMENT, HOUSING, TENANCY, GOVERNMENT BENEFITS\n- summary: No unlawful discrimination uses\n  text: or in violation of fair-housing, fair-lending, anti-discrimination, privacy, or marketing laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old and able to form a binding contract to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/atlas-red/eligibility/atlas-red-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from RED Atlas Inc's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Puerto Rico
- Data Platform
- AI Integration
- Property Records
---
