---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years of age, or the minimum age required in your jurisdiction, to use the Services.
    type: individual
  - text: If you are using the Platform or Services on behalf of a business, organization, or other legal entity, you represent and warrant that you are authorized to do so
    type: business
  minimum_age:
    text: You must be at least 13 years of age, or the minimum age required in your jurisdiction, to use the Services.
    value: '13'
  restricted_uses:
  - summary: Medical advice
    text: (i) to provide medical advice, diagnoses, treatment recommendations, or interpretations of medical results;
  - summary: Automated decisions affecting legal rights
    text: (f) for fully automated decision-making processes that may adversely affect an individual's legal rights or entitlements;
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
name: Flick
provenance_date: '2026-11-09'
provider_name: Flick
provider_slug: flick
slug: flick-eligibility
source_date: '2026-11-09'
source_filename: flick-eligibility.yml
source_heading: Eligibility
source_page: https://flick.art/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Flick\naid: flick\nurl: https://flick.art/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age, or the minimum age required in your jurisdiction, to use the Services.\n- type: business\n  text: If you are using the Platform or Services on behalf of a business, organization, or other legal entity,\n    you represent and warrant that you are authorized to do so\nrestricted_uses:\n- summary: Medical advice\n  text: (i) to provide medical advice, diagnoses, treatment recommendations, or interpretations\
  \ of medical results;\n- summary: Automated decisions affecting legal rights\n  text: (f) for fully automated decision-making processes that may adversely affect an individual's legal rights\n    or entitlements;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age, or the minimum age required in your jurisdiction, to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/flick/eligibility/flick-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Flick's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Video
- Filmmaking
- Media and Entertainment
- Creative Tools
- Content Creation
---
