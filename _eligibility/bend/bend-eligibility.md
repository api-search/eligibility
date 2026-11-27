---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not be in violation of any embargoes, export controls, or other laws of the United States or other countries having jurisdiction over Our Terms, Bend and Yourself.
  entity_types:
  - text: You must be 13 years of age or older to use Our Services and provide certain information to use Our Services.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Medical use
    text: BEND IS NOT A MEDICAL SERVICE PROVIDER AND DOES NOT OFFER MEDICAL ADVICE OR ANY OTHER PROFESSIONAL, THERAPEUTIC OR COUNSELING SERVICES.
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
name: Bend
provenance_date: '2026-11-09'
provider_name: Bend
provider_slug: bend
slug: bend-eligibility
source_date: '2026-11-09'
source_filename: bend-eligibility.yml
source_heading: Eligibility
source_page: https://bend.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bend\naid: bend\nurl: https://bend.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not be in violation of any embargoes, export controls, or other laws of the United States or other\n    countries having jurisdiction over Our Terms, Bend and Yourself.\nentity_types:\n- type: individual\n  text: You must be 13 years of age or older to use Our Services and provide certain information to use Our Services.\nrestricted_uses:\n- summary: Medical use\n  text: BEND IS NOT A MEDICAL SERVICE PROVIDER AND DOES NOT OFFER MEDICAL ADVICE OR ANY OTHER PROFESSIONAL, THERAPEUTIC\n\
  \    OR COUNSELING SERVICES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bend/eligibility/bend-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Bend's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Fitness
- Mobile App
- Wellness
---
