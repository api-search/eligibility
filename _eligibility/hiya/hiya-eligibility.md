---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Hiya makes no representation that the Services are available for use in any particular location.
  entity_types:
  - text: If you are a business entity or otherwise intend to use Hiya services for any commercial purpose, you must enter into a separate agreement with Hiya
    type: business
  minimum_age:
    text: The Services are not for use by anyone under the age of 13 years.
    value: 13 (16 if under EU/GDPR scope)
  restricted_uses:
  - summary: No marketing or telemarketing use of Hiya Data
    text: Use any Hiya Data for marketing purposes, including, but not limited to, making telemarketing calls
  - summary: No commercial use without Commercial Use Agreement
    text: You may not use Hiya services for any commercial purpose unless you have entered into a Commercial Use Agreement with Hiya.
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
name: Hiya
provenance_date: '2026-11-09'
provider_name: Hiya
provider_slug: hiya
slug: hiya-eligibility
source_date: '2026-11-09'
source_filename: hiya-eligibility.yml
source_heading: Eligibility
source_page: https://www.hiya.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hiya\naid: hiya\nurl: https://www.hiya.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Hiya makes no representation that the Services are available for use in any particular location.\nentity_types:\n- type: business\n  text: If you are a business entity or otherwise intend to use Hiya services for any commercial purpose, you must\n    enter into a separate agreement with Hiya\nrestricted_uses:\n- summary: No marketing or telemarketing use of Hiya Data\n  text: Use any Hiya Data for marketing purposes, including, but not limited to, making telemarketing\
  \ calls\n- summary: No commercial use without Commercial Use Agreement\n  text: You may not use Hiya services for any commercial purpose unless you have entered into a Commercial Use Agreement\n    with Hiya.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: 13 (16 if under EU/GDPR scope)\n  text: The Services are not for use by anyone under the age of 13 years.\n"
source_yaml_url: https://artifacts.apis.io/hiya/eligibility/hiya-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Hiya's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice Security
- Caller ID
- Branded Calling
- Spam Protection
- Scam Protection
- Deepfake Detection
- Voice Authentication
- Telecommunications
- Call Analytics
---
