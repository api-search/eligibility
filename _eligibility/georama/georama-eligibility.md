---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The terms “you,” “your,” “yours,” and equivalent terms refer in each case to the individual (whether acting individually or representing a corporate entity) who accesses or uses the Sites
    type: individual
  - text: If you are registering or using an account on behalf of a company, entity, or organization (a “Corporate Entity”), then you represent and warrant that you are an authorized representative of that Corporate Entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older to use the Sites (or if under 18, you must be more than 13 years old and have the full written authorization of a parent or guardian to use the Sites).
    value: '18'
  restricted_uses:
  - summary: Barred persons under law
    text: You may not use the Sites if you have been barred from doing so or are otherwise barred from using the Sites under the laws (including treaties) of the US or of any other nation or jurisdiction.
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
name: Georama
provenance_date: '2026-11-09'
provider_name: Georama
provider_slug: georama
slug: georama-eligibility
source_date: '2026-11-09'
source_filename: georama-eligibility.yml
source_heading: Eligibility
source_page: https://www.qualsights.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Georama\naid: georama\nurl: https://www.qualsights.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The terms “you,” “your,” “yours,” and equivalent terms refer in each case to the individual (whether acting\n    individually or representing a corporate entity) who accesses or uses the Sites\n- type: business\n  text: If you are registering or using an account on behalf of a company, entity, or organization (a “Corporate\n    Entity”), then you represent and warrant that you are an authorized representative of that\
  \ Corporate Entity\nrestricted_uses:\n- summary: Barred persons under law\n  text: You may not use the Sites if you have been barred from doing so or are otherwise barred from using the Sites\n    under the laws (including treaties) of the US or of any other nation or jurisdiction.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the Sites (or if under 18, you must be more than 13 years old\n    and have the full written authorization of a parent or guardian to use the Sites).\n"
source_yaml_url: https://artifacts.apis.io/georama/eligibility/georama-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Georama's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Market Research
- Consumer Insights
- Qualitative Research
- Surveys
- Video
- Artificial Intelligence
- Analytics
---
